# Mindful - Mental Wellness Tracker

**Your Personal Journey to Emotional Well-being**

## About Mindful

Mindful is a beautifully designed mental wellness application that helps users track their emotional journey, identify patterns, and develop healthier mental habits. Built with React Native, it provides a safe space for daily reflection and emotional awareness.


## Core Features

### Daily Tracking
- Mood logging with emotional spectrum
- Journaling with guided prompts
- Habit tracking for mental wellness
- Customizable reminder system

### Insights & Analytics
- Emotional trend visualization
- Pattern recognition charts
- Weekly and monthly reports
- Progress milestones

### Wellness Tools
- Breathing exercises and meditation
- Gratitude journaling
- Stress management techniques
- Sleep quality tracking

## Technical Implementation

### Dependencies & Libraries
- **Navigation**: React Navigation 6.x
- **Animations**: React Native Reanimated 2
- **Charts**: React Native SVG Charts
- **State**: Redux with Persistence
- **Typography**: Custom font integration
- **Testing**: Jest & React Native Testing Library

### Development Setup

```bash
# Clone and install
git clone https://github.com/codexoy/Mental-Wellness-Tracker.git
cd Mental-Wellness-Tracker
yarn install

# iOS setup
cd ios && pod install && cd ..

# Android setup
# Ensure Android SDK and emulator are configured

# Start development
yarn start
yarn android  # or yarn ios
```

### Building the App

```bash
# Development build
yarn build:dev

# Production build
yarn build:prod

# Platform-specific builds
yarn build:ios
yarn build:android
```

## Design Philosophy

Mindful follows a human-centered design approach:
- **Minimalist Interface**: Clean, distraction-free design
- **Accessibility First**: WCAG 2.1 compliant
- **Dark/Light Themes**: Respects user preferences
- **Smooth Animations**: 60fps transitions and interactions

## Data Privacy & Security

- All data stored locally on device
- Optional cloud backup with end-to-end encryption
- No personal data shared with third parties
- GDPR and HIPAA compliant design

## Customization

```javascript
// Theme configuration example
const theme = {
  colors: {
    primary: '#667eea',
    secondary: '#764ba2',
    calm: '#a8e6cf',
    anxious: '#ffaaa5',
    // Emotional spectrum colors
  },
  typography: {
    fontFamily: 'Inter',
    weights: {
      light: '300',
      regular: '400',
      medium: '500',
      bold: '700'
    }
  }
}
```
