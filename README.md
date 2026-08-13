# RASE
RASE for UAV visual geo-localization

## Dataset

The dataset used in this work is publicly available for research purposes.

### Download

| Dataset | Download | Description |
|---|---|---|
| HEBUT-MultiWeather | [Baidu Netdisk](HEBUT-MultiWeather.zip 链接: https://pan.baidu.com/s/14m9Q4kCb8yDCeg26WZFE5Q?pwd=rase) | Self-constructed UAV–satellite cross-view geo-localization dataset |

Please download the datasets and organize them as follows.

### Dataset Structure

```text
HEBUT-MultiWeather/
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
