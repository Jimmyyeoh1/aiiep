# AI Image Editing Platform 🖼️✨

An AI-powered image editing web platform designed for effortless and professional-grade image enhancements. Built with Next.js, Tailwind CSS, Shadcn UI, MongoDB, and integrated with Cloudinary, Stripe, Clerk, and various image sources.

## 🚀 Features

- **AI Image Upscaler**: Enhance image resolution using super-resolution techniques.
- **AI Generated Fill**: Fill gaps or extend image aspect ratios intelligently.
- **Object Removal**: Remove unwanted elements with simple natural language prompts.
- **Color Replacement**: Modify object colors with ease via text input.
- **Background Removal**: Isolate the subject and eliminate background automatically.
- **Image Source Integration**: Upload images from Google Drive, Dropbox, Unsplash, GettyImages, Shutterstock, and iStock.
- **Profile Dashboard**: View recent edits, token usage, and manage account details.
- **Secure Authentication**: Login/signup using Clerk with optional 2FA.
- **Payment Integration**: Pay-as-you-go token model via Stripe.
- **Public Edits Gallery**: View and download AI-edited images shared by users.

## 🛠 Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/), [Tailwind CSS](https://tailwindcss.com/), [Shadcn UI](https://ui.shadcn.com/)
- **Backend**: [TypeScript](https://www.typescriptlang.org/), [MongoDB](https://www.mongodb.com/)
- **Authentication**: [Clerk](https://clerk.dev/)
- **Image Processing**: [Cloudinary](https://cloudinary.com/)
- **Payments**: [Stripe](https://stripe.com/)
- **Hosting**: [Vercel](https://vercel.com/)
- **Other APIs**: Google Auto Tagging, Media Uploader API

## 📦 Installation

```bash
git clone https://github.com/yourusername/ai-image-editor.git
cd ai-image-editor
npm install
```
🔑 Environment Variables

Create a .env.local file with the following:
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=...
CLERK_SECRET_KEY=...
MONGODB_URL=...
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=...
STRIPE_SECRET_KEY=...
STRIPE_WEBHOOK_SECRET=...


🧪 Running Locally
npm run dev
App will be live at aiiep.vercel.app



🧠 Project Highlights

    Agile methodology used for iterative development

    Built for social media influencers, photographers, and content creators

    Pay-per-use model makes advanced editing affordable

    Usability-focused UI with natural language support

📚 Acknowledgments

    Supervised by: Ms Wahidah Binti Abdul Wahab

    Developed for TARUMT, Bachelor of Software Engineering (Hons)

    Special thanks to family, friends, and faculty members

📄 License

This project is developed for academic purposes. Contact the developer for reuse or licensing.
📬 Contact

    Developer: Yeoh Khye Shyan

    Email: yeohjim@gmail.com

    Live Demo: aiiep.vercel.app



