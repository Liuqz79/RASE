# RASE
RASE for UAV visual geo-localization

## Dataset

The dataset used in this work is publicly available for research purposes.

### Download

| Dataset | Download | Description |
|---|---|---|
| HEBUT-MultiWeather | [Baidu Netdisk](https://pan.baidu.com/s/14m9Q4kCb8yDCeg26WZFE5Q?pwd=rase) | Self-constructed UAV–satellite cross-view geo-localization dataset |

Please download the datasets and organize them as follows.

### Dataset Organization

HEBUT-MultiWeather consists of six sub-datasets collected under different
seasonal, weather, and illumination conditions. All six subsets follow the
same train/test partition.

For each subset:
| Split | View | Images | Classes |
|---|---|---:|---:|
| Train | Drone | 167 | 167 |
| Train | Satellite | 167 | 167 |
| Test | Query-Drone | 58 | 58 |
| Test | Gallery-Satellite | 225 | 225 |

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
├── 04_Sunny_late_spring/
├── 05_Late_spring_after_rain/
└── 06_Late_spring_at_night/
    ├── train/
    │   ├── drone/
    │   └── satellite/
    └── test/
        ├── query_drone/
        └── gallery_satellite/
