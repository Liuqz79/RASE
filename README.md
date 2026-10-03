# RASE

RASE for UAV visual geo-localization.

## Dataset

The dataset used in this work is publicly available for research purposes.

### Download

| Dataset | Download | Description |
|---|---|---|
| HEBUT-MultiWeather | [Google Drive](https://drive.google.com/file/d/17kLgmI33c70WGoLqRhmXtUKkzPAnijki/view?usp=drive_link) | Self-constructed UAV–satellite cross-view geo-localization dataset |

Please download the dataset and organize it as follows.

### Dataset Structure

```text
HEBUT-MultiWeather/
├── 01_Sunny_winter/
│   ├── train/
│   │   ├── drone/
│   │   └── satellite/
│   └── test/
│       ├── query_drone/
│       └── gallery_satellite/
├── 02_Winter_after_snow/
├── 03_Sunny_early_spring/
├── ...
├── 06_Late_spring_at_night/
├── 07_Cloudy_summer/
└── 08_Cloudy_autumn/
    ├── train/
    │   ├── drone/
    │   └── satellite/
    └── test/
        ├── query_drone/
        └── gallery_satellite/
```

### Dataset Organization

HEBUT-MultiWeather consists of eight sub-datasets collected under different
seasonal, weather, and illumination conditions. All eight subsets follow the
same train/test partition and directory structure.

The eight subsets are:

1. `01_Sunny_winter`
2. `02_Winter_after_snow`
3. `03_Sunny_early_spring`
4. `04_Sunny_late_spring`
5. `05_Late_spring_after_rain`
6. `06_Late_spring_at_night`
7. `07_Cloudy_summer`
8. `08_Cloudy_autumn`

For each subset:

| Split | View | Images | Classes |
|---|---|---:|---:|
| Train | Drone | 167 | 167 |
| Train | Satellite | 167 | 167 |
| Test | Query-Drone | 58 | 58 |
| Test | Gallery-Satellite | 225 | 225 |

### Sub-dataset Description

| Sub-dataset | Condition |
|---|---|
| `01_Sunny_winter` | Sunny winter |
| `02_Winter_after_snow` | Winter after snow |
| `03_Sunny_early_spring` | Sunny early spring |
| `04_Sunny_late_spring` | Sunny late spring |
| `05_Late_spring_after_rain` | Late spring after rain |
| `06_Late_spring_at_night` | Late spring at night |
| `07_Cloudy_summer` | Cloudy summer |
| `08_Cloudy_autumn` | Cloudy autumn |

## Citation

If you find this work or dataset useful in your research, please consider citing our work.

```bibtex
@article{RASE,
  title   = {RASE},
  author  = {},
  journal = {},
  year    = {}
}
```

## Acknowledgement

We thank the authors and contributors of the related open-source projects and
datasets that supported this work.

## License

The HEBUT-MultiWeather dataset is provided for academic research purposes only.
Please follow the corresponding usage requirements when using the dataset.
