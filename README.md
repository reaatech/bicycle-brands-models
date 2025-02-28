# 🏍️ Bicycle Brands & Models Dataset

This repository contains an **Open Source dataset of bicycle brands, models, and sizes**, extracted from a collection of 25,000+ real-world bicycle listings. The data is structured by brand, with each brand's file containing unique models and their corresponding size details.

## 📂 Directory Structure

```
/bicycle-brands-models
│── /brands          # Contains JSON files for each brand
│── README.md        # This documentation
```

- `/brands`: Contains individual JSON files for each brand (e.g., `santa-cruz.json`, `giant.json`).
- `README.md`: Documentation about the dataset.

## 🌜 Dataset Overview

Each brand JSON file contains structured data about bicycle models, including:

- **Brand Name** (`brand`)
- **List of Models**, each with:
    - `model`: The model name
    - `type`: The bicycle category (e.g., **Gravel, Mountain, Road**)
    - `ebike`: Boolean indicating if it is an eBike
    - `suspension`: Suspension type, if applicable
    - `sizes`: Available sizes, each with:
        - `size`: The size label (e.g., **M, L, XL**)
        - `frame_size`: The numerical frame size (if available)
        - `rider_height_min`: Suggested minimum rider height
        - `rider_height_max`: Suggested maximum rider height
        - `measurement_unit`: Unit of measurement (usually `cm`)

### 📌 Example JSON Format (Santa Cruz)

```json
{
  "brand": "Santa Cruz",
  "models": [
    {
      "model": "Stigmata Force AXS / Carbon CC / 700c",
      "type": "Gravel",
      "ebike": false,
      "suspension": null,
      "sizes": [
        {
          "size": "M",
          "frame_size": 56,
          "rider_height_min": 174,
          "rider_height_max": 184,
          "measurement_unit": "cm"
        }
      ]
    }
  ]
}
```

---

## 🔍 How to Use This Data

You can use this dataset for:
- **Bicycle eCommerce websites**: Organize and filter models and sizes.
- **Bike classification & categorization**: Standardize bike models.
- **Data visualization & analytics**: Compare brands, frame sizes, and trends.
- **Machine Learning / AI applications**: Build recommendation models for bikes.

---

## 🚀 Getting Started

Clone the repository:

```sh
git clone https://github.com/reaatech/bicycle-brands-models.git
cd bicycle-brands-models
```

---

## 💌 Contributions

- If you find errors or missing data, feel free to **submit an issue**.
- If you want to improve the dataset, **fork the repo and submit a pull request**.

---

## 🌟 License

This dataset is open-source and available under the **MIT License**. Feel free to use, modify, and share!

---

## 📞 Contact

For questions or collaborations, reach out via GitHub Issues.

