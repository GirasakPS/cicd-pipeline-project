FROM node:18-alpine
WORKDIR /app

# Copy package.json และติดตั้ง dependencies ก่อน
COPY package*.json ./
RUN npm install

# ค่อย copy ไฟล์อื่น ๆ ภายหลัง
COPY . .

# รันแอป
CMD ["node", "app.js"]

