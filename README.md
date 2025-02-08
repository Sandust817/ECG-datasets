# ECG Dataset

This dataset contains electrocardiogram (ECG) data collected for the purpose of heart condition classification. The data is provided in two lead types: **single lead** and **three leads**. Each record contains ECG data in three files:

- `.hea`: Contains the metadata of the ECG signal, such as sampling rate, ECG type, and other information.
- `.dat`: Contains the processed ECG signal data.
- `.atr`: Contains the label information, such as the heart condition.

## Data Structure

The dataset is divided into two main folders based on the ECG type:
1. **singlelead**: Contains records from single-lead ECG devices.
2. **threelead**: Contains records from three-lead ECG devices.

Each record is stored in its own folder, named as `record_001`, `record_002`, etc. The folder contains three files:
- `record_001.hea`: Metadata for the record.
- `record_001.dat`: The ECG signal data.
- `record_001.atr`: The label for the record (such as `AF`, `ABNORMAL`, or `NORMAL`).

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

## License

This dataset is provided under the [Your License Here] license.

## Citation

If you use this dataset in your research, please cite the following paper:

> Author, Title, Journal/Conference, Year.
