# 🕐 World Clock - Digital Time Zone Display

A beautiful, interactive digital clock that displays the current time across multiple time zones with real-time updates and a stunning UI.

## ✨ Features

- **Real-time Updates**: Times update every second with millisecond precision
- **Multiple Time Zones**: Pre-configured with 22 major world cities
- **Add/Remove Zones**: Dynamically add or remove time zones as needed
- **Time Format Toggle**: Switch between 12-hour and 24-hour formats
- **UTC Offset Display**: Shows UTC offset for each timezone
- **Sort Functionality**: Arrange clocks by time for easy comparison
- **Persistent Storage**: Your timezone selections are saved in the browser
- **Beautiful UI**: Modern gradient design with smooth animations and hover effects
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **No Dependencies**: Pure HTML, CSS, and JavaScript - no external libraries required

## 📦 What's Included

```
📄 digital-clock.html - Complete standalone HTML file with embedded CSS and JavaScript
```

## 🚀 Getting Started

### Option 1: Direct Usage
1. Download or clone the repository
2. Open `digital-clock.html` in your web browser
3. Start using the world clock immediately!

### Option 2: Online Viewing
Visit the file directly on GitHub and click "Raw" to open it in the browser.

## 🌍 Pre-configured Time Zones

The clock comes with these cities pre-configured:

| City | Timezone |
|------|----------|
| New York | America/New_York |
| London | Europe/London |
| Tokyo | Asia/Tokyo |
| Sydney | Australia/Sydney |
| Dubai | Asia/Dubai |
| Los Angeles | America/Los_Angeles |
| Singapore | Asia/Singapore |
| Hong Kong | Asia/Hong_Kong |
| Berlin | Europe/Berlin |
| Paris | Europe/Paris |
| India | Asia/Kolkata |
| Bangkok | Asia/Bangkok |
| Istanbul | Europe/Istanbul |
| São Paulo | America/Sao_Paulo |
| Mexico City | America/Mexico_City |
| Moscow | Europe/Moscow |
| Toronto | America/Toronto |
| Vancouver | America/Vancouver |
| Auckland | Pacific/Auckland |
| Seoul | Asia/Seoul |
| Shanghai | Asia/Shanghai |
| Manila | Asia/Manila |

## 🎮 How to Use

### Basic Operations

1. **Add a Timezone**
   - Select a timezone from the dropdown menu
   - Click "Add Timezone" button
   - The new clock appears immediately

2. **Remove a Timezone**
   - Click the "Remove" button on any clock card
   - The timezone is removed instantly

3. **Toggle Time Format**
   - Click "Toggle 12/24 Hour" to switch between formats
   - All clocks update simultaneously

4. **Sort Clocks**
   - Click "Sort by Time" to arrange clocks chronologically
   - Helpful for finding specific times across zones

5. **Reset to Default**
   - Click "Reset to Default" to return to the original 3 time zones
   - (New York, London, Tokyo)

### Data Persistence

- Your selected timezones are automatically saved to browser storage
- Preferences persist across browser sessions
- Clear browser data to reset selections

## 🎨 Design Features

- **Gradient Background**: Purple-blue gradient backdrop
- **Card-based Layout**: Each timezone in a beautiful card with shadow effects
- **Hover Animations**: Smooth 3D lift effect on hover
- **Responsive Grid**: Automatically adjusts columns based on screen size
- **Color Scheme**: Modern purple and white with excellent contrast

## 💻 Technical Details

### Technology Stack
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with gradients, flexbox, and grid
- **JavaScript (ES6+)**: Modern JavaScript with Intl API for internationalization

### Browser Compatibility
- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Mobile browsers: ✅ Full support

### Key Functions

```javascript
initializeClocks()        // Initialize the clock on page load
updateAllClocks()        // Update all clock displays
addTimezone()           // Add a new timezone
removeTimezone(tz)      // Remove a timezone
toggleFormat()          // Toggle between 12/24 hour
sortClocks()           // Sort clocks by time
resetClocks()          // Reset to default timezones
saveTimezones()        // Save selections to localStorage
```

## 📱 Responsive Breakpoints

- **Desktop**: 3-4 columns (250px+ per clock)
- **Tablet**: 2 columns
- **Mobile**: 1 column (full width)

## 🔧 Customization

### Adding More Time Zones

Edit the `timezones` array in the JavaScript section:

```javascript
const timezones = [
    { name: 'Your City', tz: 'Continent/City' },
    // ... more timezones
];
```

### Changing Colors

Modify the gradient colors in the CSS:

```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Adjusting Update Interval

Change the interval in JavaScript (currently 1000ms):

```javascript
setInterval(updateAllClocks, 1000); // Update every second
```

## 📝 Example Use Cases

- **International Teams**: Track time zones for remote team members
- **Global Businesses**: Monitor business hours across regions
- **Travel Planning**: Check times before scheduling calls
- **Education**: Learn about world time zones interactively
- **Event Planning**: Coordinate events across multiple regions

## 🐛 Known Limitations

- Daylight Saving Time is handled by the browser's Intl API
- Times are based on the system clock accuracy
- Browser storage has typical limits (5-10MB)

## 🚀 Future Enhancements

Potential features for future versions:

- [ ] Dark mode toggle
- [ ] Custom timezone naming
- [ ] Time until next event
- [ ] World map visualization
- [ ] Alarm/reminder functionality
- [ ] Share timezone links
- [ ] Import/export settings
- [ ] Weather integration

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Improve documentation
- Submit pull requests

## 📞 Support

For issues, questions, or suggestions, please open an issue on GitHub.

## 🎯 Tips & Tricks

1. **Bookmark the page** for quick access
2. **Use in multiple windows** to compare different timezone selections
3. **Export to PDF** using your browser's print function
4. **Mobile home screen**: Add to home screen on mobile devices for app-like usage

---

**Last Updated**: August 2026  
**Version**: 1.0  
**Status**: Stable ✅
