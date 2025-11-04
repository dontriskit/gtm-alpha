---
title: MDX & Markdown Cheatsheet - Berkeley Windsurfing
description: A comprehensive guide to Markdown and MDX syntax
author: Wind Enthusiast
tags: [markdown, mdx, berkeley, windsurfing]
---


# MDX & Markdown Cheatsheet: Berkeley Windsurfing Edition

This guide demonstrates Markdown and MDX features using Berkeley windsurfing as our theme.

## Headings

# H1: Windsurfing at Berkeley Marina
## H2: Best Spots in the San Francisco Bay
### H3: Equipment Rentals
#### H4: Wind Conditions by Season
##### H5: Safety Tips
###### H6: Local Clubs and Communities

## Text Formatting

**Bold text**: The **Golden Gate Bridge** provides iconic views while windsurfing.

*Italic text*: Berkeley Marina offers *excellent* conditions for beginners.

***Bold and Italic***: The San Francisco Bay has ***world-class*** windsurfing.

~~Strikethrough~~: ~~Alameda Beach~~ Berkeley Marina is the preferred spot.

`Inline code`: Check wind speed with `windspeed --location berkeley`

## Lists

### Unordered List
- Berkeley Marina
- Crissy Field
- Candlestick Point
- Sherman Island
  - Advanced riders only
  - Strong currents

### Ordered List
1. Check wind forecast
2. Prepare equipment
3. Launch from Berkeley Marina
4. Sail towards Alcatraz
5. Return before sunset

### Task List
- [x] Reserve windsurfing board
- [x] Check weather conditions
- [ ] Pack wetsuit
- [ ] Arrive at Berkeley Marina by 10 AM

## Links and Images

[Berkeley Windsurfing Association](https://example.com/berkeley-windsurfing)

[Wind Forecast][forecast]

[forecast]: https://example.com/wind-forecast "Bay Area Wind Conditions"

![Berkeley Marina Windsurfer](https://example.com/windsurfer.jpg)

![Windsurfing][windsurf-img]

[windsurf-img]: https://example.com/action.jpg "Catching air at Berkeley"

## Blockquotes

> Windsurfing in Berkeley is not just a sport, it's a lifestyle.
>
> The San Francisco Bay offers some of the most consistent winds in California.

> **Pro Tip:**
>
> Always check the wind direction before launching. Northwest winds are ideal for Berkeley Marina.

## Code Blocks

### JavaScript Example
```javascript
function checkWindSpeed(location) {
  if (location === 'Berkeley Marina' && windSpeed > 15) {
    return 'Perfect windsurfing conditions!';
  }
  return 'Check forecast again';
}
```

### Python Example
```python
def best_windsurfing_time():
    spots = {
        'Berkeley Marina': '12pm - 4pm',
        'Crissy Field': '2pm - 6pm',
        'Sherman Island': '10am - 5pm'
    }
    return spots
```

### Bash Example
```bash
# Check wind conditions
curl https://api.weather.com/berkeley-wind
echo "Ready to windsurf!"
```

## Tables

| Location | Wind Speed | Skill Level | Best Season |
|----------|------------|-------------|-------------|
| Berkeley Marina | 15-25 mph | Beginner-Intermediate | Spring/Summer |
| Crissy Field | 20-30 mph | Intermediate-Advanced | Year-round |
| Sherman Island | 25-35 mph | Advanced | Summer |
| Candlestick Point | 18-28 mph | Intermediate | Spring/Fall |

### Table with Alignment

| Spot | Avg Wind | Difficulty |
|:-----|:--------:|-----------:|
| Berkeley Marina | 18 mph | Easy |
| Crissy Field | 25 mph | Moderate |
| Sherman Island | 30 mph | Hard |

## Horizontal Rules

Berkeley Marina is perfect for beginners.

---

Crissy Field offers challenging conditions.

***

Sherman Island is for experts only.

## MDX Components

### Custom JSX Component Example

<div className="wind-alert">
  <h3>⚠️ High Wind Warning</h3>
  <p>Winds expected to exceed <strong>30 mph</strong> at Berkeley Marina today!</p>
</div>

### Nested Components

<div style={{backgroundColor: '#e3f2fd', padding: '20px', borderRadius: '8px'}}>
  <h4>🏄 Today's Conditions</h4>
  <ul>
    <li><strong>Wind:</strong> 22 mph NW</li>
    <li><strong>Temperature:</strong> 68°F</li>
    <li><strong>Water Temp:</strong> 58°F</li>
  </ul>
</div>

## Inline HTML

Berkeley Marina offers <mark>exceptional windsurfing</mark> opportunities.

The water temperature is <sub>approximately</sub> 58°F in <sup>summer</sup>.

<details>
  <summary>Advanced Techniques</summary>

  - Water starts
  - Jibing
  - Planing
  - Jumping waves
</details>

## Emphasis and Special Characters

Use &copy; 2025 Berkeley Windsurfing Club

Temperature: 68&deg;F | Wind: 15&ndash;25 mph

San Francisco &rarr; Berkeley Marina

## Footnotes

Berkeley Marina is the best spot for learning to windsurf[^1].

The Golden Gate Bridge provides stunning backdrop[^2].

[^1]: According to local windsurfing instructors, 90% of beginners start here.
[^2]: Visible from most windsurfing spots in the Bay.

## Escaping Characters

\*This text is surrounded by literal asterisks\*

\# This is not a heading

\[This is not a link\]

## Definition Lists (if supported)

<dl>
  <dt>Windsurf Board</dt>
  <dd>A surfboard with an attached sail used for windsurfing</dd>

  <dt>Berkeley Marina</dt>
  <dd>A popular windsurfing destination on the San Francisco Bay</dd>

  <dt>Planing</dt>
  <dd>When the board rises up and skims across the water surface</dd>
</dl>

## Automatic Links

https://berkeleywindsurfing.com

contact@berkeleywindsurfing.com

## Mixed Content Example

<div className="location-card">

## 📍 Berkeley Marina

**Address:** 201 University Ave, Berkeley, CA 94710

**Features:**
- Free launch area
- Parking available
- Wetsuit rentals nearby
- Beginner-friendly

```bash
# Directions
# From SF: Take I-80 East, exit University Ave
# Drive time: ~25 minutes
```

> *"The best windsurfing spot in the East Bay!"* - Local Rider

</div>

---

## Summary

This cheatsheet covers:
1. ✅ All major Markdown syntax elements
2. ✅ MDX component integration
3. ✅ Code blocks with syntax highlighting
4. ✅ Tables and formatting
5. ✅ Berkeley windsurfing content throughout

**Happy windsurfing at Berkeley Marina!** 🏄‍♂️💨