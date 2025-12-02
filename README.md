# Iloilo Province Interactive Map

An offline HTML application showcasing the municipalities and cities of Iloilo Province in the Western Visayas region of the Philippines.

## Features

### 🗺️ Interactive Map
- **SVG-based map** showing all 42 municipalities and 1 component city
- **Click-to-select** functionality for each municipality
- **Visual highlighting** of selected areas
- **Color-coded** areas:
  - Green: Municipalities
  - Orange: Component City (Passi City)
  - Light Green: Iloilo Province boundary

### 🔍 Search & Navigation
- **Real-time search** functionality
- **Alphabetical listing** of all municipalities
- **Filter results** as you type
- **Click-to-navigate** from sidebar to map

### 📊 Municipality Information
- **Official details** for each municipality:
  - Type (Municipality/Component City)
  - Classification (First Class, Second Class, etc.)
  - Current Mayor
  - Geographic location details

### 📱 Mobile-Optimized Design
- **Fully responsive** layout for all screen sizes
- **Touch-optimized** interface with proper touch targets (48px minimum)
- **Mobile-specific** enhancements for iOS and Android
- **Landscape/Portrait** orientation support
- **No zoom interference** - prevents unwanted mobile zooming
- **Touch feedback** with visual and haptic responses
- **Auto-focus search** on mobile devices for better usability
- **Optimized for high-DPI** displays and retina screens
- **Hidden scrollbars** for cleaner mobile interface

### 💾 Offline Capability
- **No internet required** - all data embedded
- **Self-contained** HTML file
- **Fast loading** and smooth performance

### 🗺️ Map Accuracy
- **Geographically accurate** based on reference maps and official boundaries
- **Properly clustered** northeastern municipalities reflecting actual layout
- **Accurate province shape** that matches Iloilo's distinctive outline
- **Corrected coastal positioning** for southeastern municipalities
- **Updated based on verified geographical references** for maximum accuracy

## Coverage Area

### Administrative Divisions
- **43 Local Government Units (LGUs)**
  - 42 Municipalities
  - 1 Component City (Passi City)
  - 1 Highly Urbanized City (Iloilo City - provincial capital)

### Geographic Distribution
- **Northern Coast**: Carles, Balasan, Estancia, Batad, San Dionisio, Sara
- **Northeastern Region**: Lemery, Concepcion, Ajuy
- **Eastern Coast**: Barotac Viejo, Banate, Anilao, Barotac Nuevo, Dumangas, Zarraga, Leganes, Pavia
- **Southeastern Coast**: Iloilo City (Capital), Oton
- **Southern Coast**: Tigbauan, Guimbal, Miagao, San Joaquin
- **Western Region**: Igbaras, Tubungan, Leon, Alimodian, Maasin, Janiuay, Lambunao
- **Central Region**: Calinog, Bingawan, Dueñas, Badiangan, Dingle, Mina, Pototan, Cabatuan, New Lucena, Santa Barbara, San Miguel, San Rafael, San Enrique

## Mobile Features

### 📱 Mobile-Specific Optimizations
- **Automatic mobile detection** and layout adjustment
- **Touch-friendly** municipality selection on map
- **Auto-focus** search box for quick navigation
- **Landscape mode** support with side-by-side layout
- **Portrait mode** with stacked layout for easy scrolling
- **iOS Safari optimizations** including tap highlighting removal
- **Android Chrome optimizations** for smooth touch response
- **High-DPI display support** for crisp graphics on retina screens
- **Prevents unwanted zooming** while maintaining accessibility

### 🎯 Touch Interactions
- **Tap to select** municipalities on the map
- **Touch feedback** with visual confirmation
- **Improved touch targets** meeting accessibility standards (48px minimum)
- **Smooth scrolling** in municipality lists
- **Orientation-aware** layout changes

## How to Use

1. **Open the file**: Double-click on `iloilo_map.html` to open in your web browser
2. **Desktop**: Click on any municipality/city on the map
3. **Mobile**: Tap on any municipality/city on the map
4. **Search**: Use the search box to find specific municipalities
5. **View details**: Selected municipality information appears in the sidebar
6. **Navigate**: Click/tap on municipality names in the sidebar list

## Map Accuracy Verification

The map has been **geographically corrected** to accurately represent Iloilo Province:

### ✅ **Corrected Features**
- **Northeastern "Panhandle"**: Municipalities are now properly clustered as shown in reference maps
- **Province Boundary**: Updated to match the actual irregular outline of Iloilo
- **Coastal Layout**: Southeastern municipalities repositioned to reflect true geographic relationships
- **Municipal Clusters**: Northern municipalities properly grouped and positioned
- **Capital Positioning**: Iloilo City correctly placed in southeastern coastal region

### 📍 **Key Improvements**
- **CARLES** at the northernmost tip (as reference shows)
- **BALASAN**, **ESTANCIA** properly positioned along the coast
- **Central Cluster**: San Dionisio, Batad, Sara, Lemery, Concepcion, Ajuy in correct relative positions
- **Coastal Arc**: Southeastern municipalities (Iloilo City, Oton, Tigbauan, Guimbal, Miagao, San Joaquin) properly aligned

## Technical Details

- **Pure HTML/CSS/JavaScript** - no external dependencies
- **SVG vector graphics** for crisp display at any resolution
- **Advanced responsive CSS** with multiple breakpoints
- **Touch event handling** for both click and touch interactions
- **Mobile detection** with device-specific optimizations
- **Orientation change** handling for landscape/portrait modes
- **iOS Safari & Android** specific fixes and enhancements
- **High-DPI display** optimization
- **Cross-browser compatible** including mobile browsers

## Data Source

Municipal information including:
- Official municipality names
- Current mayors and contact information
- Administrative classifications
- Geographic boundaries

## File Structure

```
iloilo_map.html - Main application file (contains everything)
README.md - This documentation file
```

## Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

*Created by MiniMax Agent - An interactive map application for educational and reference purposes.*