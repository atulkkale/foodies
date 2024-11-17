# Foodies 🍔🍕🍜

Foodies is a Next.js application built using the latest **Next.js app router** and its **server component features**. This project integrates **AWS S3** for image storage and **better-sqlite3** as the database. With Foodies, users can explore meals shared by others, view detailed information about meals, and contribute by sharing their own meals with uploaded pictures.

## Features 🚀

- **Explore Meals**: Browse meals shared by other users.
- **Meal Details**: View detailed information about each meal by clicking on "View Details."
- **Share Your Meals**: Users can add their own meals with descriptive details.
- **Image Upload**: Upload a picture of the meal while creating it using AWS S3 for secure storage.
- **Fast & Efficient**: Built with the latest Next.js app router and server components for optimized performance.
- **Database**: Uses better-sqlite3 for seamless database management.

## Technologies Used 🛠️

- **Framework**: [Next.js](https://nextjs.org/) (App Router and Server Components)
- **Database**: [better-sqlite3](https://github.com/WiseLibs/better-sqlite3)
- **Cloud Storage**: [AWS S3](https://aws.amazon.com/s3/)
- **Deployment**: [Vercel](https://vercel.com/)

## Installation & Setup 🧑‍💻

1. Clone the repository:
   
```bash
git clone https://github.com/atulkkale/foodies.git
cd foodies
```

2. Install dependencies:

```bash
npm install
```

3. Configure environment variables:

- Add your AWS S3 bucket details in a .env file.

```bash
AWS_ACCESS_KEY_ID=your-access-key-id
AWS_SECRET_ACCESS_KEY=your-secret-access-key
AWS_BUCKET_NAME=your-bucket-name
AWS_REGION=your-region
```

4. Start the development server:

```bash
npm run dev
```

5. Open your browser and visit:

```bash
http://localhost:3000
```

## Project Link

Check out the live version of the Foodies:
[Foodies on Vercel](https://foodies-next-js-app.vercel.app/)

## Future Improvements ✨

- **User Authentication**: Add login and signup functionality to allow personalized experiences.
- **Meal Rating System**: Allow users to rate meals and provide feedback.
- **Search and Filter**: Implement search and filter options to easily find meals by categories, ingredients, or user ratings.
- **Edit and Delete Meals**: Enable users to edit or delete their previously shared meals.
- **Favorites Feature**: Add the ability for users to save favorite meals for easy access.
- **Pagination**: Introduce pagination for smoother browsing when the number of meals grows significantly.
- **Responsive Design Enhancements**: Improve the user experience on smaller devices.

## Screenshots 📸

<img width="1680" alt="Screenshot 2024-11-17 at 10 04 00 PM" src="https://github.com/user-attachments/assets/8af3be9e-98c5-4aee-810d-47306706258c">

<img width="1680" alt="Screenshot 2024-11-17 at 10 04 12 PM" src="https://github.com/user-attachments/assets/f497339b-e583-466d-b28a-af7c58ce611f">

<img width="1680" alt="Screenshot 2024-11-17 at 10 04 29 PM" src="https://github.com/user-attachments/assets/40b7ccd9-73bd-407c-9cd0-f1a86b1b617b">

## Contributing 🤝

Contributions are welcome! If you have ideas for new features or improvements, feel free to open an issue or create a pull request.
