# stage: 2 — the production environment
FROM nginx:alpine
COPY — from=react-build /app/build /usr/share/nginx/html
EXPOSE 80
CMD [“nginx”, “-g”, “daemon off;”]