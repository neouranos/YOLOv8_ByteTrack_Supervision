# YOLOv8 + ByteTrack + Supervision

## Step by step to run the code
1. Install [Python 3.10.11](https://www.python.org/downloads/release/python-31011/). When installing, checklist Add python.exe to PATH.

2. Install [YOLOv8](https://github.com/ultralytics/ultralytics).
    ```
    pip install ultralytics
    ```

3. Install [Supervision](https://github.com/roboflow/supervision).
    ```
    pip install supervision[desktop]
    ```

4. If using an RTX GPU: 

    4.1 Uninstall the previous torch using command below.
    ```
    pip uninstall torch torchvision torchaudio
    ```

    4.2 Install the [pytorch](https://pytorch.org/get-started/locally/) with GPU.
    ```
    pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
    ```