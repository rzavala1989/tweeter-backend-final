Tweeter backend fork:

1. Clone the repo
2. Install dependencies with `npm install --legacy-peer-deps`
3. docker-compose up -d (to run database)
4. make database migrations with `npm run typeorm migration:run -d src/api/database/index.ts`
5. Test against backend with swagger: http://localhost:3000/docs/
6. Run the app with `npm run dev`
