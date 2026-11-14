# Dataset source and limitations

Source candidate: https://huggingface.co/datasets/AliArshad/Bugzilla_Eclipse_Bug_Reports_Dataset

The notebook's saved preview contains 88,682 records and columns `Project`, `Bug ID`, `Severity Label`, `Resolution Status`, and `Short Description`. The source and notebook have not been independently checked for byte-for-byte identity.

The dataset CSV is not redistributed here. Verify the publisher's license and redistribution terms before sharing the data. The notebook indicates the records are FIXED bug reports, and severity labels are imbalanced; results may not generalize to new/unresolved reports.

To run: obtain the CSV lawfully, place it at `/content/drive/MyDrive/software_bugs.csv` in Google Colab or edit the notebook path, then run all cells in order.
