## <Speech_to_Text>

### [Architecture]
#### 1. File Upload(.mp4)
  * run.py

#### 2. Convert /.mp4 to /.wav
  * process_video.py
    - use moviepy
  
#### 3. Upload Google Cloud Storage
  * upload_to_gcloud.py
    - Files of 1 minute or longer play time should store in GCS bucket
    - Save to bucket(GCS), upload it
  
#### 4. Google Speech_to_Text API
  * goog.py  
  
#### 5. Write Text File
  * write_file.py(2 options)
    - Make Speech_to_Text + Speech Diarization file
    - Make only Speech_to_Text file
    
#### 6. Run
  * run.py


### [In Progress]
#### 1. requirements.txt
  - 이것저것 깔아보면서 하느라 폴더안에 정리를 다 못했습니다..!!
  
#### 2. Code comments
