# 🍺 My Beer Brewing Corner 🍻

Welcome to My Beer Brewing Corner! This is an open-source collection of craft beer recipes and comprehensive brewing knowledge, designed to help both beginners and experienced brewers.

## 🌐 Interactive Website

Visit the interactive website at: **[https://petroff.se/brew/](https://petroff.se/brew/)**

The website features:
- 📚 Interactive brewing guides
- 🍺 Featured recipes with descriptions
- 🗂️ Complete brewing vault with all recipes
- 📱 Mobile-friendly responsive design

## 📚 Brewing Guides

### 🎓 Complete Homebrewing Guide
![Homebrewing Guide](https://github.com/art-defcon/beer/blob/main/src/img/homebrewing_guide.png?raw=true)

A comprehensive 19-slide interactive presentation covering everything from grain to glass:
- Essential equipment and costs
- Sanitization best practices
- Understanding brewing terminology (OG, FG, IBU, SRM, etc.)
- Mash temperature control and enzyme activity
- Step-by-step brewing process
- Pressure fermentation techniques
- Troubleshooting common problems
- Advanced tips for water chemistry and yeast management


### 🏭 Brewery Scale & Recipe Formats
![Brewery Scale Comparison](https://github.com/art-defcon/beer/blob/main/src/img/brewery_scale.png?raw=true)

An educational presentation explaining the evolution from homebrew to industrial production:
- Production scale overview (homebrew to industrial)
- Recipe format comparison (BeerXML vs Brewfather JSON vs ISA-88)
- Equipment and automation at different scales
- Quality control and compliance requirements

## 🍻 Featured Recipes

### Hurry Up IPA
![Hurry Up IPA](https://github.com/art-defcon/beer/blob/main/src/img/ipa_beer_glass_tapped_foamy_cloudy.jpeg?raw=true)

An American IPA featuring tropical and citrus notes from Amarillo and Mosaic hops. Fermented with Voss Kveik yeast for a quick turnaround without sacrificing flavor.
- **Style:** American IPA
- **ABV:** 6.5%
- **IBU:** 65
- **Format:** [Brewfather JSON](BrewfatherJson/HurryUpIPA.json)

### NEPA (New England Pale Ale)
![NEPA](https://github.com/art-defcon/beer/blob/main/src/img/nepa_glass_beer_foamy.jpeg?raw=true)

A hazy, juicy pale ale showcasing Citra, Galaxy, and Mosaic hops. Lower ABV makes it perfect for session drinking while maintaining that tropical fruit explosion.
- **Style:** New England Pale Ale
- **ABV:** 4.8%
- **IBU:** 35
- **Format:** [Brewfather JSON](BrewfatherJson/NEPANewEnglandPaleAle.json)

### Wheat IPA
A delicious wheat-forward IPA with citrusy hops, combining the smoothness of wheat with bold hop character.
- **Style:** Wheat IPA
- **Format:** [BeerXML](BeerXML/wheat_ipa_by_claude37.xml)

## 📋 Recipe Formats

### 🌾 BeerXML
Industry-standard XML format supported by most brewing software:
- BeerSmith
- Brewer's Friend
- BeerTools
- And many others

BeerXML files contain complete recipe details including fermentables, hops, yeast, mash schedules, and water profiles.

### 🧪 Brewfather JSON
Modern JSON format for the Brewfather app, offering:
- Cloud-based recipe management
- Real-time sync across devices
- Brewing session tracking
- Inventory management
- Water chemistry calculations

## 📂 Repository Structure

```
beer/
├── index.html                    # Main website
├── BeerXML/                     # Classic XML format recipes
│   └── wheat_ipa_by_claude37.xml
├── BrewfatherJson/              # Modern JSON format recipes
│   ├── HurryUpIPA.json
│   └── NEPANewEnglandPaleAle.json
├── src/
│   ├── brewing-guide.html       # Complete homebrewing guide
│   ├── brewery-scale-comparison.html  # Scale comparison presentation
│   └── img/                     # Images for guides and recipes
```

## 🔍 Usage

### Importing Recipes
- **BeerXML files:** Import directly into BeerSmith, Brewer's Friend, or any software supporting the BeerXML standard
- **Brewfather JSON files:** Import directly into the Brewfather app

## 📜 License and 🤝 Contributing

This project is open source. All recipes and guides are free to use, modify, and share.

Feel free to:
- Fork this repository
- Try the recipes and suggest improvements

---

**Happy Brewing!** 🍺 

*Remember: The best beer is the one you brew yourself!*
