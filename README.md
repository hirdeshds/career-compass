# AssistEdge
<img width="1080" height="564" alt="image" src="https://github.com/user-attachments/assets/d960ccf5-24c5-4f18-8ed7-5e5db93daf80" />



A comprehensive career preparation platform featuring AI-powered interview preparation, resume building, document verification, and secure face-based authentication.

## Features

- **Interview Preparation**: AI-generated interview questions tailored to specific companies and roles
- **Resume Builder**: Generate multiple resume versions (ATS-Optimized, Project-Focused, Elegant Modern)
- **Document Verification**: Validate resume and academic documents for authenticity
- **Face Authentication**: Secure login/registration using Amazon Rekognition

## Tech Stack

- React + TypeScript
- Vite
- Tailwind CSS
- shadcn/ui
- Framer Motion

## Getting Started

```sh
# Clone the repository
git clone <YOUR_GIT_URL>

# Navigate to the project directory
cd <YOUR_PROJECT_NAME>

# Install dependencies
npm install

# Start the development server
npm run dev
```

### AWS Services Required

1. **Amazon Rekognition** - Face-based authentication (IndexFaces, SearchFacesByImage)
2. **Amazon S3** - Store face images and documents
3. **Amazon DynamoDB** - User data storage
4. **AWS Lambda** - Serverless functions for registration and login
5. **Amazon API Gateway** - REST API endpoints

## Project Structure

```
src/
├── components/
│   ├── home/          # Landing page components
│   ├── layout/        # Navbar, Layout wrapper
│   └── ui/            # shadcn/ui components
├── pages/
│   ├── Index.tsx          # Landing page
│   ├── InterviewPrep.tsx  # Interview question generator
│   ├── ResumeBuilder.tsx  # Resume generator
│   ├── Verification.tsx   # Document verification
│   ├── FaceAuth.tsx       # Face authentication
│   └── AWSSetupDocs.tsx   # AWS integration docs
└── hooks/             # Custom React hooks
```
## Team - TechZNinjas
## Members
- MAHEK BHATIA (Team Leader)
- HIRDESH 
- GAURAV SHUKLA
- HARSH DEEP 
- JAHANVI SRIVASTVA


