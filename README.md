# TrendAI

TrendAI is a modern, Instagram-inspired e-commerce platform built to seamlessly blend the engagement of a social media feed with intelligent, AI-powered shopping experiences.

## Features

- **Social-Driven Shopping Feed:** Scroll through a lively, Instagram-style interface complete with a horizontal Story reel and a vertical feed of product posts, heavily inspired by modern social applications.
- **Immersive AI Shopping Assistant:** A full-screen interactive AI chat experience that acts as a personal fashion stylist. Features a ChatGPT-like persistent sidebar which saves and loads your chat history.
- **OWS Wallet Checkout Integration:** A fully localized automated mock payment process integrated directly into the cart via OWS.
- **Polished, Modern UI/UX:** Built with a warm, soft-toned aesthetic and sleek interactions using `shadcn/ui` components and smooth Tailwind CSS animations.
- **Complete English Localization:** The entire application interface and user experience are fully localized in English.

## Tech Stack

- **Framework:** [Next.js](https://nextjs.org/) (React)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Components:** [shadcn/ui](https://ui.shadcn.com/)
- **Icons:** [Lucide React](https://lucide.dev/)
- **API Mocking:** DummyJSON

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/medine1729/trendAIOWS.git
   cd trendyAI
   ```

2. **Install the dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   You will need a `.env.local` file at the root of the project to run the AI and backend services securely. Ask the repository contributors for securely generating API keys (e.g., Google/Gemini or Firebase keys).

4. **Run the development server:**
   ```bash
   npm run dev
   ```

5. **Explore the App:**
   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Usage Highlights

- Navigate the **Home** feed to discover curated products the same way you explore social media posts.
- Click **AI Chat** from the navigation to interact with the interactive fashion assistant to find personalized outfits.
- Add items to your cart, navigate to checkout, and experience the integrated **OWS Wallet payment gateway**.

## License

This project is licensed under the MIT License.
