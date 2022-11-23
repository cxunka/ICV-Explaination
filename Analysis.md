# Color Sensitive

- Black Widow (Global Feature)
    - Head (Hair Shape)
    - Clothes (Black) (Conflict: Loki)

- Captain America (Partial Feature)
    - Star (On the chest) (Classify: Spider Man)
    - Shield (Conflict: Spider Man) (Frequent: Always)
    - Clothes (Blue)

- Doctor Strange (Global Feature)
    - Clothes (Blue, Red) (Conflict: Spider Man)

- Hulk (Global Feature)
    - Muscle Texture (Global Only) (Gradient Sensitive)
    - Skin (Green)

- IronMan (Global Feature)
    - Color (Red, Yellow)

- Loki (Partial Feature)
    - Head (Helmet Shape) (Sometimes)
    - Clothes (Black) (Conflict: Black Widow)

- Spider Man (Partial Feature)
    - Spider Symbol (On the chest) (Classify: Captain America)
    - Shield (Conflict: Captain America) (Frequent: Sometimes)
    - Clothes (Blue, Red) (Conflict: Captain America)

- Thanos (Global Feature)
    - Head (Texture)
    - Skin (Purple)

# Singleton
## Cloth / Skin Color
- Hulk
- Thanos

# Conflict Pairs
## Cloth / Skin Color
### Mainly Black: __(Black Widow, Loki)__
Level: __Difficult__

Classify By: Head Shape?

### Mainly Red: __(Iron Man, Spider Man)__
Level: __Medium__
Classify By: Icon on chest

Classify By: Secondary Color {Iron Man: Yellow, Spider Man: Blue}

### Red & Blue: __(Spider Man, Doctor Strange)__ 
Level: __Difficult__

Classify By: Body Shape

## Weapon
### Shield: __(Captain America, Spider Man)__
Level: __Easy__

Classify By: Body Color {Captain America: Blue, Spider Man: Red}

# TradeOff
- Partial / Global Feature
- Number of Layers
- Size of Layers
- 