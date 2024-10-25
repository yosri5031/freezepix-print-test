# FreezePIX - Photo Printing Service

A web application for ordering photo prints online. Users can upload their photos, select print sizes, and place orders which are then sent to the lab for processing.

## Features

- Photo upload from mobile or desktop
- Multiple print size options
- Order tracking with unique FP-XXX format
- Automated email notifications
- Responsive design

## Technology Stack

- Next.js
- TypeScript
- TailwindCSS
- Node.js
- Nodemailer

## Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/freezepix.git
cd freezepix
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env.local` file with the following variables:
```
EMAIL_USER=your-email@example.com
EMAIL_PASSWORD=your-email-password
```

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Deployment

The application is configured for deployment on Heroku. Follow these steps:

1. Create a Heroku account and install the Heroku CLI
2. Login to Heroku CLI:
```bash
heroku login
```

3. Create a new Heroku app:
```bash
heroku create freezepix-app
```

4. Set environment variables:
```bash
heroku config:set EMAIL_USER=your-email@example.com
heroku config:set EMAIL_PASSWORD=your-email-password
```

5. Deploy:
```bash
git push heroku main
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details
