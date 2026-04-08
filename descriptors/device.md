# Device-level metadata descriptor

Explains the list of devices in `device.yaml`.

Each entry describes one device used in the study.

---

## Key fields and guidance

### `device_id`
Unique ID linking devices to datasets.

### `device_name`
Human-readable name.

### `manufacturer`, `model`
Recommended for reproducibility.

### `device_type`
Common values:
- blood pressure monitor  
- EGC electrodes  
- tonometer
- ingestible pill
- continuous glucose monitor
- peripheral body temperature sensor
- psychophysical measurement system
- visual stimulation and pupillometry system
- optical coherence tomograph
- psychomotor vigilance test/wearable physiological monitor  

### `measurement_modalities`
List of what the device measures (e.g., `blood pressure`, `alertness`).

### `calibration`
Record calibration events where relevant.

### `placement`
Typical body or environmental location.

### `documentation_links`
Article, protocols, manuals, datasheets, etc.
