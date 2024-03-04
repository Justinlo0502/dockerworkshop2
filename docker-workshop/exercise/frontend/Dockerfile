FROM node:18
COPY . /app/
WORKDIR /app
RUN npm install
ENV PORT=8000
ENV REACT_APP_BACKEND_URL=http://localhost:8000
CMD ["npm", "start"]