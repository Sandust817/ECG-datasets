# ECGhm2025

This dataset contains electrocardiogram (ECG) data collected for the purpose of heart condition classification. The data is provided in two lead types: **single lead** and **three leads**. Each record contains ECG data in three files:

- `.hea`: Contains the metadata of the ECG signal, such as sampling rate, ECG type, and other information.
- `.dat`: Contains the processed ECG signal data.
- `.atr`: Contains the label information, such as the heart condition.

## Data Structure

The dataset is divided into two main folders based on the ECG type:
1. **singlelead**: Contains records from single-lead ECG devices.
2. **threelead**: Contains records from three-lead ECG devices.

Each record is stored in its own folders. The folders contains json files.That's json description:
`Id`: Unique identifier of data;
`EcgType`: device type; 1-Single lead device 2-Triple lead device; The sampling rate is uniformly 256
`Result`: Data label; `AF`: Suspected atrial fibrillation; `ABNORMAL`: Suspected abnormal rhythm; `NORMAL`: Normal rhythm.
`Data`: ECG data; ECG1: Channel 1 data ECG2: Channel 2 data ECG3: Channel 3 data. To convert to millivolts, the formula is: data * 1.05 * 1000/(4095 * 70)

## ECG Types

- **Single-lead ECG**: Data from a single ECG lead.
- **Three-lead ECG**: Data from three ECG leads.

## Label Categories

The dataset includes the following labels for the heart conditions:
- **AF**: Atrial fibrillation (suspected).
- **ABNORMAL**: Abnormal rhythm.
- **NORMAL**: Normal heart rhythm.

## Usage

This dataset can be used for training and testing ECG classification algorithms. You can use the `.dat` files for ECG signal analysis, the `.atr` files for the corresponding labels, and the `.hea` files for metadata and sampling rate.

## Download

You can download this dataset at 链接: https://pan.baidu.com/s/1038fkW77DKoTZpwdr8WWuA, extracted code is: p3sd.

## License

This dataset is provided under the [Your License Here] license.

## Citation

If you use this dataset in your research, please cite the following paper:


