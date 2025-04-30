# Interactive Movie Data Visualization

An interactive compound visualization analyzing top 50 movies from 2016, exploring their Bechdel test results and gender distribution in casting roles.

## Features

📊 **Three Interactive Sub-Charts**
- **Left & Right Panels**: Heatmaps showing gender distribution across role types
- **Center Panel**: Vertical text plot displaying movie rankings
- **Interactive Highlighting**: Select any movie row to highlight across all panels
- **Bechdel Test Encoding**: Color highlights based on Bechdel test results (1=green/0=red)

## Data Sources

🎬 **Datasets**:
1. `top50_2016.csv`: Contains movie rankings, box office data, and Bechdel test results
2. `castGender.csv`: Contains detailed cast member information with gender breakdown

📚 **Bechdel Test**: [Learn more](https://bechdeltest.com/)

## Installation

1. Clone repository:
   ```bash
   git clone [https://github.com/yourusername/movie-visualization.git](https://github.com/KellyLuMinrong/data-visualization/blob/main/data_visualization.ipynb)
   cd movie-visualization
   ```

2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Place datasets in `data/` directory
2. Run Jupyter notebook:
   ```bash
   jupyter notebook 
   ```
3. Output will be saved as `C:\Users\kellyloo\Downloads\data_visualization.ipynb`

## Visualization Details

✅ **Key Technical Features**:
- Data merging and preprocessing
- Horizontal concatenation of Altair charts
- Movie ranking-based sorting
- Interactive selection using Altair's `selection_single`
- Custom color encoding for Bechdel results
- Axis customization and text overlays

## Dependencies

- Python 3.7+
- pandas
- altair
- vega_datasets

## Project Structure

```
├── data/
│   ├── top50_2016.csv
│   └── castGender.csv
├── C:\Users\kellyloo\Downloads\data_visualization.ipynb
```

## Contributing

Contributions welcome! Please open an issue first to discuss proposed changes.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Acknowledgments

- ECON7910 Course Staff for project guidelines
- Altair development team for visualization tools
- Bechdeltest.com for test criteria
