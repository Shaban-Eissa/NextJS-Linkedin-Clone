# NextJS LinkedIn Clone

<img src="https://github.com/Shaban-Eissa/NextJS-Linkedin-Clone/assets/49924090/bb0bb239-1aa1-4997-9ee9-6d1303ccec9a" width="400" height="100" />

A clone of the LinkedIn website built using Next.js, React, and MongoDB. This project aims to replicate the core features of LinkedIn, providing a responsive and dynamic web application.


## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Technologies](#technologies)
- [Contributing](#contributing)


## Features

- **User Authentication:** log in, and log out securely with NextAuth.
- **Feed:** Post creation and there is delete feature to delete post, and interact with others' posts in a real-time activity feed.


## Demo

<img src="https://github.com/Shaban-Eissa/NextJS-Linkedin-Clone/assets/49924090/3eb599a3-c8d3-4e40-bb99-7cbde824e92b" width="900" height="380" />

Check out the live demo https://nextjs-linkedin-clone-pi.vercel.app


## Installation

1. Clone the repository:

```bash
git clone https://github.com/Shaban-Eissa/NextJS-Linkedin-Clone.git
cd NextJS-Linkedin-Clone
```

2. Install dependencies:

```bash
npm install
```

3. Set up MongoDB:
    
     Install and set up MongoDB. Replace the placeholders in the application code with your MongoDB connection details.
  
4. Environment Variables
     Setting Environment Variables
      For local development, create a `.env` file in the root of your project and add the following:

      ```env
      GOOGLE_CLIENT_ID=your_google_client_id
      GOOGLE_CLIENT_SECRET=your_google_client_secret
      NEXTAUTH_URL=http://localhost:3000
      JWT_SECRET=your_jwt_secret
      MONGODB_URI=your_mongodb_uri
      MONGODB_DB=your_mongodb_db
      NEWS_API_KEY=your_news_api_key
      
5. Run the application:
    

```bash
npm run dev
```

Visit `http://localhost:3000` in your browser to see the app.




## Technologies Used

- **Next.js:** React framework for building server-rendered React applications.
- **React:** JavaScript library for building user interfaces.
- **Tailwind CSS:** Utility-first CSS framework for styling.
- **Framer Motion:** Animation library for React to create smooth and expressive UI animations.
- **MongoDB:** A NoSQL database for storing application data.
- **NextAuth:** Authentication library for Next.js applications.
- **Recoil:** State management library for managing global state in React applications.
- **Material-UI (MUI):** React components for building a Material Design-based user interface.



## Contributing

Contributions are welcome! Please feel free to open issues or submit pull requests.
