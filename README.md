# Bus Ticket Client - Frontend Application

A comprehensive bus ticket booking frontend built with React, Vite, Firebase, Stripe, and Ant Design. Features include seat selection, payment processing, and real-time updates.

## Features

- **Modern UI:** Ant Design components
- **Payment Integration:** Stripe payment gateway
- **Authentication:** Firebase authentication
- **Real-time Updates:** React Query for data fetching
- **Interactive Maps:** Seat selection interface
- **Date Picker:** Easy date selection
- **PDF Generation:** Ticket PDF with jsPDF
- **Responsive Design:** Mobile-friendly interface
- **Loading States:** Skeleton loading animations
- **Tooltips:** Interactive tooltips

## Technologies Used

- **Framework:** React + Vite
- **UI Library:** Ant Design
- **State Management:** React Query
- **Authentication:** Firebase
- **Payment:** Stripe
- **Charts:** Recharts
- **Slider:** Swiper
- **Styling:** Tailwind CSS, SASS
- **Date Handling:** Moment.js, React Datepicker
- **Notifications:** SweetAlert2

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Firebase project
- Stripe account

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Jewel-190237/bus-ticket-client.git
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file with the following variables:
   ```env
   VITE_API_URL=your_backend_api_url
   VITE_FIREBASE_API_KEY=your_firebase_api_key
   VITE_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
   VITE_FIREBASE_PROJECT_ID=your_firebase_project_id
   VITE_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and visit `http://localhost:5173`

## Project Structure

```
bus-ticket-client/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── context/
│   ├── utils/
│   ├── App.jsx
│   └── main.jsx
├── .env
├── package.json
├── vite.config.js
├── tailwind.config.js
└── README.md
```

## Features in Detail

### Seat Selection
- Interactive seat map
- Real-time availability
- Price calculation
- Seat category filtering

### Payment Processing
- Stripe integration
- Secure card payments
- Payment confirmation
- Invoice generation

### User Dashboard
- Booking history
- Ticket downloads
- Profile management
- Rating system

### Admin Features
- Bus management
- Schedule management
- Revenue tracking
- User management

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Contributing

Feel free to fork this project and create pull requests for any improvements.

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

**Jewel-190237**
- GitHub: [Jewel-190237](https://github.com/Jewel-190237)
- Email: jewel190237@gmail.com
