# ImageStatistic

Export CSV and Image according to brightness value

## Installation

Select your Python version ( Python 3.6.8)
--------------------------

Create enviroment
```bash
python -m virtualenv myenv
```

Activate enviroment
```bash
myenv\Scripts\activate.bat 
```

Install lib
```bash
pip install -r requirements.txt
```

## Usage

Download 3 Folder Image in GoogleDrive
Add 3 Folder to Folder's name "image" in this repo

Separate Image
```
python separate_image.py
```

Run this to extract all image in Separate Image
```
python extract_total.py
```

or change code in export.py file and run this to export specify dir
```python
# Uncomment this line, img_dir is img directory, csv_dir is destination csv directory, "ea1a2c91-f485-4eab-9ddf-2c56249393ca" is csv name, "success" is extra name
# export_csv_image(img_dir, csv_dir, "ea1a2c91-f485-4eab-9ddf-2c56249393ca", "success")
```
```
python export.py
```

