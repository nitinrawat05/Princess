# 👑 Disney Princess Dataset

This dataset contains detailed characteristics, narrative elements, and popularity metrics for Disney princess characters. It spans from film metadata to social media engagement, allowing for a rich analysis of character development, cultural representation, and commercial success.

## 📁 Dataset Overview

- **Rows:** Each row represents a version or appearance of a Disney princess.
- **Columns:** 35 features covering movie details, character traits, story elements, and popularity indicators.

---

## 🧾 Column Descriptions

| Column Name               | Data Type   | Description |
|---------------------------|-------------|-------------|
| `PrincessName`            | string      | Name of the Disney princess. |
| `FirstMovieTitle`         | string      | Title of the first movie in which the princess appeared. |
| `FirstMovieYear`          | integer     | Year the first movie was released. |
| `MovieRuntimeMinutes`     | integer     | Total runtime of the movie in minutes. |
| `NumberOfSongs`           | integer     | Number of songs featured in the movie. |
| `HasSoloSong`             | boolean     | Indicates if the princess sings a solo song (`Yes` / `No`). |
| `HasDuet`                 | boolean     | Indicates if the princess sings a duet (`Yes` / `No`). |
| `HairColor`               | string      | Primary hair color of the princess. |
| `EyeColor`                | string      | Eye color of the princess. |
| `OutfitPrimaryColor`      | string      | Main color of the princess's outfit. |
| `OutfitStyleEra`          | string      | Fashion era or time period reflected in the princess’s clothing (e.g., "Victorian", "Modern"). |
| `IsRoyalByBirth`          | boolean     | Whether the princess is born royal (`Yes` / `No`). |
| `HasAnimalSidekick`       | boolean     | Whether the princess has an animal sidekick. |
| `SidekickType`            | string      | Type of animal sidekick (e.g., "Dragon", "Horse", "Fish"). |
| `HasMagicalPowers`        | boolean     | Indicates if the princess possesses magical powers. |
| `MagicType`               | string      | Type of magic (e.g., "Healing", "Ice", "None"). |
| `MainSetting`             | string      | Main geographic or thematic setting (e.g., "Forest", "Desert", "Castle"). |
| `IsBasedOnRealStory`      | boolean     | Whether the story is based on real events or legends. |
| `CulturalOrigin`          | string      | Cultural or ethnic background represented by the princess. |
| `SpeaksToAnimals`         | boolean     | Whether the princess can communicate with animals. |
| `FightsVillainDirectly`   | boolean     | Whether the princess engages the main villain in conflict. |
| `RomanticSubplot`         | boolean     | Indicates if the story includes a romantic subplot. |
| `MarriedByEnd`            | boolean     | Whether the princess is married by the end of the movie. |
| `VillainName`             | string      | ⚠️ Placeholder text like "Villain of [Princess]". Should be cleaned and mapped to actual names. |
| `VillainType`             | string      | Archetype of the villain (e.g., "Witch", "Sorcerer", "Stepmother"). |
| `IMDB_Rating`             | float       | IMDb rating of the movie (0-10). |
| `RottenTomatoesScore`     | integer     | Rotten Tomatoes critic score (0-100). |
| `BoxOfficeMillions`       | float       | Worldwide box office earnings in millions USD. |
| `AvgScreenTimeMinutes`    | integer     | Average screen time of the princess in minutes. |
| `NumMerchItemsOnAmazon`   | integer     | Count of merchandise items available on Amazon. |
| `GoogleSearchIndex2024`   | integer     | Google Search popularity index (2024). |
| `InstagramFanPages`       | integer     | Number of Instagram fan pages for the princess. |
| `TikTokHashtagViewsMillions` | float    | Total TikTok views of hashtags (in millions). |
| `Top3Hashtags`            | string      | Top 3 hashtags related to the princess, separated by space. |
| `IsIconic`                | boolean     | Whether the princess is considered iconic. |
| `PopularityScore`         | integer     | Composite popularity score (0-100). |

---

## ⚠️ Data Cleaning Notes

- `VillainName` contains placeholder values such as "Villain of Mulan". These should be replaced with actual villain names for accurate analysis.
- Ensure consistency across boolean fields (`Yes` / `No`) by standardizing their format.
- Multiple entries exist for the same princess in different years — useful for analyzing evolution across movies or versions.

---

## 💡 Use Cases

- Analyzing trends in representation (e.g., cultural diversity, magical powers, sidekicks).
- Studying evolution of Disney storytelling (romance, combat roles, fashion).
- Tracking character-based popularity on social media.
- Comparing commercial success (box office vs. merchandise vs. online presence).

---

## 📌 License

Feel free to use this dataset for educational, research, or non-commercial projects. Please credit appropriately if you publish insights based on it.

---

