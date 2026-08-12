Input: document.jpg 


<img width="960" height="1280" alt="img_scan" src="https://github.com/user-attachments/assets/9ec5dae4-4c1b-4f93-8f54-095cada67e0a" />






Output: document_scanner Pipeline:

Read image →
grayscale →
blur →
edges →
contours →
page detection →
perspective correction →
CLAHE →
adaptive threshold →
morphology.


<img width="662" height="1068" alt="outputs_document_scan" src="https://github.com/user-attachments/assets/128d6cdc-fd59-4a10-920b-78942116b7fa" />
