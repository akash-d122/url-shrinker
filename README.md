
# URL Shrinker

**URL Shrinker** is a full-stack application that allows users to shorten URLs, track analytics, generate QR codes, and more. Built with **ReactJS**, **Supabase**, and **Shadcn UI**, this app features robust authentication, a modern UI, and scalable deployment options.




## 🚀 Features

- **Full Stack Development:** Create a complete URL shortener app using ReactJS and Shadcn UI.
- **User Authentication:** Implement user sign-up and login using Supabase for secure access.
- **Analytics Tracking:** Track clicks and provide analytics for shortened URLs to users.
- **QR Code Generation:** Generate QR codes for shortened URLs to enhance usability.
- **Modern UI Design:** Utilize Tailwind CSS and Shadcn UI for a sleek and responsive interface.
- **API Integration:** Connect the front end and back end for seamless URL management.
- **Deployment Guidance:** Steps for deploying the application to a hosting service.



## 🔍 Key Insights

- **User-Centric Design:** Prioritize user experience through intuitive UI components like FAQs and input forms, ensuring easy navigation and interaction.
- **Data Management:** Set up a PostgreSQL database in Supabase to store URLs and click data, facilitating robust analytics.
- **Authentication Flow:** Implement a context API for managing user state, enhancing security and streamlining the authentication process across the app.
- **Real-Time Features:** Track URL analytics and provide instant feedback on user interactions to improve engagement.
- **Role-Level Security:** Ensure that user data remains protected with role-based access control.
- **Error Handling:** Enhance reliability with effective error handling in forms and user feedback mechanisms.
- **Scalability in Deployment:** Discuss deployment strategies and potential improvements to ensure the app is prepared for growth and can adapt to user needs over time.



## 🛠️ Getting Started


### Prerequisites
- **Node.js** (v14 or higher)
- **ReactJS** (v17 or higher)
- **Supabase** Account
- **Tailwind CSS** and **Shadcn UI**
   
 ## Installation

 1. **Clone the repository:**
    ```bash
    git clone https://github.com/akash-d122/url-shrinker.git
    cd url-shrinker
    ```

 1. **Install dependencies:**

    ```bash
    npm install
    ```

 1. **Set up Supabase:**
   - Create a new project in Supabase.

   - Obtain your Supabase URL and API key.

   - Add these details to a .env file:

      ```env
      REACT_APP_SUPABASE_URL=your-supabase-url
      REACT_APP_SUPABASE_ANON_KEY=your-supabase-anon-key
      ```

 4. **Start the development server:**

    ```bash
    npm run dev
    ```
## Deployment

- Vercel / Netlify: Refer to the deployment section in the documentation to deploy the app easily on Vercel or Netlify.



## 📈 Usege

### User Authentication
- Sign Up: Register with your email and password.
- Login: Access the app with your credentials.
### URL Shortening
- Shorten URL: Enter a long URL and click "Shorten."
- View Shortened URL: Copy or share the generated short URL.
### Analytics
- View Clicks: Track the number of clicks for each URL.
- Data Visualization: View analytics in graphical form.
### QR Code Generation
- Generate QR Code: A QR code is created for each shortened URL.
### ⚙️ API Integration
- Endpoints: Document any available API endpoints.
- Authentication: Describe how API authentication works.
## 🚀 Deployment
### Vercel
   - Deploy to Vercel:
      - Sign up or log in to Vercel.
      - Connect your GitHub repository.
      - Vercel will automatically detect and deploy the application.
### Netlify
   - Deploy to Netlify:
      - Sign up or log in to Netlify.
      - Connect your GitHub repository.
      - Configure the build settings (build command: npm run build, publish directory: build).

## 🤝 Contributions
   Contributions are welcome! Please check the issues page for ongoing discussions or open a new issue.

## 📧 Contact
For questions or further information, email akashduddekunta@gmail.com.
