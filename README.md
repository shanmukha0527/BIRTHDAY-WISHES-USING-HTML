# Animated Birthday Cake

A beautiful, animated birthday cake created with pure HTML, CSS, and SVG. This project features smooth animations including a building cake, flickering candle flame, and flowing frosting effects.

## Features

- Pure CSS and SVG animations (no JavaScript required)
- Multi-layered cake that builds sequentially
- Animated candle with realistic flickering flame
- Smooth frosting animations
- Responsive design that works on all devices
- Customizable text and colors
- Lightweight and fast loading

## How It Works

The animation sequence includes:

1. **Cake Layers** (2-4 seconds): Three cake layers animate and build from bottom to top
2. **Frosting Flow** (4-6 seconds): Cream animates and flows between the layers
3. **Candle Drop** (6 seconds): White candle slides down and positions on top
4. **Flame Animation** (6.5 seconds): Multiple flickering flame layers begin and loop continuously

## Usage

1. Download the `birthday-cake.html` file
2. Open it in any modern web browser
3. The animation will start automatically

## Customization

### Change the Name
Edit the name in the HTML:
```html
<p class="name">Your Name Here</p>
```

### Modify Colors
Update the CSS color values:
```css
/* Cake color */
path[fill="#a88679"] { fill: "#your-color"; }

/* Frosting color */
path[fill="#fefae9"] { fill: "#your-color"; }
```

### Adjust Timing
Modify animation delays in the CSS:
```css
/* Candle appears after 6 seconds */
.cake { animation: in 500ms 6s ease-out forwards; }

/* Flame starts at 6.5 seconds */
.fuego:nth-child(1) { animation: fuego 2s 6.5s infinite; }
```

### Custom Message
Change the birthday message:
```html
<h1>Your Custom Message!</h1>
```

## Browser Support

Works in all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge
- Mobile browsers

## File Structure

- `birthday-cake.html` - Complete HTML file with embedded CSS and SVG
- Self-contained with no external dependencies (except Google Fonts)
- File size: approximately 8KB

## Technical Details

- **Animation Type**: CSS keyframes and SVG path animations
- **Graphics**: Scalable Vector Graphics (SVG)
- **Typography**: Google Fonts (Lato)
- **Styling**: CSS3 with animations and transforms
- **Performance**: Optimized for smooth 60fps animations

## Use Cases

- Digital birthday cards
- Website birthday greetings
- Email birthday messages
- Social media posts
- Party invitations
- Personal celebrations

## License

This project is open source and available under the MIT License.

## Credits

Created using modern web technologies:
- HTML5
- CSS3 Animations
- SVG Graphics
- Google Fonts
