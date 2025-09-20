# Frontend Coding Challenge - Complete Implementation Plan

## Project Structure
```
YourRollNumber/
├── README.md
├── Logging Middleware/
│   ├── logger.ts
│   ├── types.ts
│   └── README.md
└── Frontend Test Submission/
    ├── app/
    │   ├── page.tsx
    │   ├── layout.tsx
    │   └── globals.css
    ├── components/
    │   ├── AuthForm.tsx
    │   └── LoggingDemo.tsx
    ├── lib/
    │   └── auth.ts
    ├── .env.local
    ├── package.json
    ├── next.config.js
    └── tsconfig.json
```

## Step-by-Step Implementation Plan

### Phase 1: Repository Setup
1. Create GitHub repository named with your roll number
2. Initialize with proper folder structure
3. Set up .gitignore (exclude .env.local, node_modules)
4. Create initial README without "Affordmed" mentions

### Phase 2: Logging Middleware Development
1. Create TypeScript types for LogLevel and FrontendPackage
2. Implement logToServer function with proper error handling
3. Add comprehensive type safety and validation
4. Include JSDoc documentation

### Phase 3: Next.js Application Setup
1. Initialize Next.js 14 with App Router
2. Configure TypeScript and environment variables
3. Set up basic UI components
4. Implement authentication flow

### Phase 4: Integration & Testing
1. Import logging middleware into Next.js app
2. Create demonstration UI with log level buttons
3. Implement state management for auth token
4. Add error handling and user feedback

### Phase 5: Documentation & Screenshots
1. Update README with setup instructions
2. Capture desktop and mobile screenshots
3. Document API interactions in Network tab
4. Final code review and optimization

## Environment Variables Required
```
NEXT_PUBLIC_EMAIL=your_email@abc.edu
NEXT_PUBLIC_NAME=Your Name
NEXT_PUBLIC_ROLL_NO=your_rollno
NEXT_PUBLIC_ACCESS_CODE=your_access_code
NEXT_PUBLIC_CLIENT_ID=your_client_id
NEXT_PUBLIC_CLIENT_SECRET=your_client_secret
```

## API Endpoints
- Auth: http://20.244.56.144/evaluation-service/auth
- Logs: http://20.244.56.144/evaluation-service/logs

## Key Requirements Checklist
- [x] TypeScript implementation
- [x] Production-grade code quality
- [x] No "Affordmed" references
- [x] Proper error handling
- [x] Bearer token authentication
- [x] All log levels supported
- [x] Frontend package types
- [x] Environment variable security