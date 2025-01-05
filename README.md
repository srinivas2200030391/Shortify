
# Shortify - Simplify Long URLs

Shortify is a powerful, user-friendly URL shortening service designed to simplify long URLs into compact, shareable links. With support for custom aliases, analytics, and seamless redirection, Shortify provides an easy way to manage and share links efficiently.

---

## Features

- **URL Shortening**: Transform long, cumbersome URLs into concise, shareable links.
- **Custom Aliases**: Create personalized short URLs with custom aliases.
- **Click Analytics**: Track the number of clicks on each shortened URL.
- **Secure Redirection**: Ensures safe and reliable redirection to the original URL.

---

## Tech Stack

Shortify is built with modern web technologies to ensure performance and scalability:

- **Frontend**: React.js, TailwindCSS
- **Database**: Supabase (PostgreSQL)
- **Routing**: React Router
- **Hosting**: Vercel

---

## Installation

Follow these steps to run Shortify locally:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/srinivas2200030391/Shortify.git
   cd Shortify-Simplify-Long-Urls
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**
   Create a `.env` file in the root directory with the following variables:
   ```env
   REACT_APP_SUPABASE_URL=your_supabase_url
   REACT_APP_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Run the Application**
   ```bash
   npm start
   ```

   The application will be available at [http://localhost:5173](http://localhost:5173).

---

## Deployment

1. **Build the Application**
   ```bash
   npm run build
   ```

2. **Deploy to Vercel**
   - Push your repository to GitHub.
   - Connect the repository to Vercel.
   - Add the environment variables in Vercel's project settings.
   - Deploy the application.

---

## How It Works

1. **Enter a URL**: Users provide the long URL they want to shorten.
2. **Generate Short URL**: Shortify creates a unique or custom alias.
3. **Share & Track**: Share the short URL and track its performance via analytics.
4. **Redirection**: Clicking the short URL redirects to the original URL.

---

## Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository.
2. Create a new branch for your feature/bug fix.
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes.
   ```bash
   git commit -m "Add your message here"
   ```
4. Push your branch.
   ```bash
   git push origin feature-name
   ```
5. Create a Pull Request.

---


## Contact

For any inquiries or support, feel free to reach out:

- **GitHub Issues**: [Shortify Issues](https://github.com/srinivas2200030391/Shortify/issues)
- **Email**: srinivaskommirisetty13@gmail.com

---

## Acknowledgments

- [Supabase](https://supabase.com) for backend and database support.
- [React Router](https://reactrouter.com) for routing.
- [Vercel](https://vercel.com) for hosting the application.

Happy Shortening! ✨

