📄 Resume Upload Portal

A modern, sleek, and responsive web application that allows users to upload, preview, view, and manage their resume files (PDF, DOC, DOCX). Built with animated UI, this portal integrates with an AWS API Gateway + S3 backend to handle file storage and retrieval.

✨ Features

    🖼 Drag & Drop Upload with animation

    ✅ File validation (PDF, DOC, DOCX only, max 5MB)

    🔍 Preview PDF in-browser and Word document info

    📊 Real-time upload progress simulation

    📁 Modal-based file listing and management

    ❌ Delete single/multiple files with checkbox selection

    🎉 Animated success & error messages

    🎨 Glassmorphism UI with smooth CSS transitions

🚀 Live Demo

    Hosted on [GitHub Pages / AWS / Netlify] – (Add link if available)

🛠️ Technologies Used

    HTML5, CSS3 (with custom animations and glassmorphism)

    Vanilla JavaScript (no frameworks)

    Font Awesome

    Ionicons

    Animate.css

    AWS API Gateway & S3 (for upload/download/delete)

📂 File Structure

📁 resume-upload-portal/
├── index.html        # Main front-end file
├── README.md         # Project documentation
└── ...               # Hosted API Gateway (not included)

⚙️ Setup Instructions
Prerequisites

    A static web server (or just open index.html in browser)

    A backend API (like AWS API Gateway + Lambda + S3)

Setup AWS Backend

    Create an S3 bucket (enable CORS).

    Create Lambda functions for:

        Upload

        List files

        Delete files

    Expose Lambda functions via API Gateway.

    Replace the API endpoint in index.html:

const API_BASE = "https://your-api-id.execute-api.region.amazonaws.com/your-stage";

✅ To Do / Improvements

Add user authentication (Cognito or Firebase)

Add version control or duplicate detection

Optimize uploads using multipart if needed

    Add pagination/search to file list

📸 Screenshots
Upload Page	File List Modal	Upload Progress
	
📄 License

MIT License. Free to use, customize, and share.
