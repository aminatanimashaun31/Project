
FROM node:17-alpine
WORKDIR /app
ARG ATLAS_URI
COPY package.json ./
RUN npm install --legacy-peer-deps
COPY . .
EXPOSE 5050
ENV ATLAS_URI=mongodb+srv://aminatanimashaun31:Kunbi87.@cluster0.k3yivs8.mongodb.net/
CMD ["npm", "run", "start"]