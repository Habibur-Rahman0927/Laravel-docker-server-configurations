# Dockerized Laravel Project

## Overview

This repository contains a Dockerized setup for a Laravel project, including PHP, Nginx, MySQL, and Node.js for frontend asset management with Vite.

## Requirements

- Docker
- Docker Compose

## Setup

   ```bash
   Run Server Configuration: docker-compose up -d --build
   Run Command: docker exec -it laravel_app /bin/bash
   git clone https://github.com/yourusername/yourlaravelproject.git .
   Do this step: 
    1. composer install
    2. cp .env.example .env // change env configurations
    3. php artisan key:generate
    4. php artisan migrate
    5. npm i && npm run dev
    6. npm run build
   

   
