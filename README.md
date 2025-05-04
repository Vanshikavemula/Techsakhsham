# Arogyam Kiosk

Arogyam Kiosk is a futuristic, modern sci-fi themed web application designed to help rural communities book telemedicine appointments with doctors. The platform provides essential healthcare features, including video consultations, medicine searches, and doctor messaging, all within a simple and functional UI.

![image](https://github.com/user-attachments/assets/4680fdb6-f4fe-4c5f-a0c0-4796b36eba44)


## Features

- **User Authentication**: Secure login, signup, and email verification using Supabase.
- **Hero Section**: A welcoming homepage with an introduction to the platform.
- **Service Cards**: Hover-enabled cards displaying key services.
- **Medicine Search**: Search for Ayurvedic and general medicines.
- **Best Doctors**: Find top-rated doctors with city-based location filtering.
- **Appointment Booking**: Schedule telemedicine appointments with available doctors.
- **News Slider**: Stay updated with trending health-related news.
- **Messaging System**: Communicate with doctors for queries.
- **Video Consultation**: Conduct telemedicine video calls via Agora.
- **Chatbot Support**: AI-powered chatbot using Hugging Face API for healthcare queries.
- **Contact Form**: Integrated with Formspree for user inquiries.
- **Profile Dashboard**: View upcoming appointments and user details.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Vanshikavemula/Techsaksham.git
   cd arogyam
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables (create a `.env` file):
   ```plaintext
   REACT_APP_SUPABASE_URL=your_supabase_url
   REACT_APP_SUPABASE_ANON_KEY=your_supabase_anon_key
   REACT_APP_AGORA_APP_ID=your_agora_app_id
   ```
4. Run the development server:
   ```bash
   npm start
   ```
