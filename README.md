# VoiceCare: AI Companion for Elderly


## 🎯 Problem Statement

- Elderly isolation and loneliness
- Medication adherence challenges
- Difficulty in managing appointments and schedules
- Need for quick emergency communication

## 🌟 Features

### 1. Medication Reminders

- Set medication reminders using voice commands
- Receive timely voice alerts for medication
- Natural language interaction for reminder management
- Example: "Set a reminder to take my pills at 8 AM"

### 2. Companionship Features

- Engaging conversations and jokes
- Weather updates
- Time checks
- Simulated music playback interaction
- Senior-friendly interactions

### 3. Appointment Scheduling

- Voice-based appointment scheduling
- Day-of-event reminders
- Natural language date and time processing
- Example: "Schedule a doctor's appointment for next Tuesday at 2 PM"

### 4. Emergency Communication

- Quick emergency alert system
- SMS notifications to predefined caregivers
- Simple voice trigger: "Call for help"
- Immediate response confirmation

## 🛠 Technologies Used

- **Voice Processing**: Eleven Labs API for natural voice synthesis
- **Speech Recognition**: Whisper/Eleven Labs for speech-to-text
- **Communication**: Twilio for SMS alerts
- **Scheduling**: Built-in scheduler for reminders and appointments
- **Frontend**: Next.js with TypeScript
- **Styling**: Tailwind CSS

## 🚀 Getting Started

First, install the dependencies:

```bash
npm install
# or
pnpm install
```

Then, run the development server:

```bash
npm run dev
# or
pnpm dev
```



## 🔑 API Keys Required

To run this project, you'll need the following API keys:

- Eleven Labs API key
- Twilio API credentials
- OpenWeatherMap API key (for weather updates)

Create a `.env` file in the root directory and add your keys:

```env
ELEVEN_LABS_API_KEY=your_key_here
TWILIO_ACCOUNT_SID=your_sid_here
TWILIO_AUTH_TOKEN=your_token_here
OPENWEATHERMAP_API_KEY=your_key_here
```

## 🎥 Demo Features

The demo showcases:

- Setting and receiving medication reminders
- Engaging in casual conversation (jokes, weather, time)
- Emergency alert system simulation
- Talk to agent by dialing Agent Phone Number
   

## 📝 Additional Notes

- Responses are optimized for elderly users with clear, slow, and friendly voice settings
- Demo includes simulated time passage for demonstration purposes
- MVP focuses on core reminder and communication features
- Future updates will include editing and deleting capabilities


