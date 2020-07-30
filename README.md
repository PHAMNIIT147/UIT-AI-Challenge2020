# UIT-AI-Challenge2020
This is an AI challenge competition held at University Information Technology Ho Chi Minh City 

# *LAB1*
## Answer:
  1. Có môi trường tương tự như Google Colab cung cấp bởi Amazon, Microsoft, IBM, etc hay không?
    -> Hiện tại có 5 môi trường được cung cấp tương tự như Google Colab có thể kể đến như sau:
      1. [Azure Notebooks](https://notebooks.azure.com/)
      2. [Kaggle](https://www.kaggle.com/google-cloud)
      3. [Amazon Sagemaker](https://aws.amazon.com/sagemaker/)
      4. [IBM DataPlatform Notebooks](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/notebooks-parent.html)
      
  23. Code của Google Colab lưu ở đâu? / Khi chương trình chạy trên Google Colab cần đọc dữ liệu thì dữ liệu lưu ở đâu?
    -> Source code **Google Colab** được lưu trữ vĩnh viễn trong [Drive](https://colab.research.google.com/notebooks/io.ipynb#scrollTo=u22w3BFiOveA) của bạn. 
    
  4. Khi chương trình chạy trên Google Colab cần đọc dữ liệu từ máy cục bộ (local computer ví dụ như desktop hay laptop của bạn) thì làm thế nào (gợi ý dùng Form)
    -> Chỉ cần thêm code vào **Google Colab** của bạn:
      ```
      from google.colab import files
      uploaded = files.upload()
      ```
  5. Cách thực thi các Cell trong Google Colab?
      -> Just hover the mouse over `[|>]` and press the play button to the upper left. Or press shift-enter to execute. Chỉ cần di chuyển con trỏ chuột đến `[_]` và nhấn nút `|>`(play) để chạy, một cách khác là dùng lệnh ngắn `shift + enter`. Theo dõi hướng dẫn từ [Google](https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l01c01_introduction_to_colab_and_python.ipynb#scrollTo=F8YVA_634OFk).
      
  6. Cách đổi sang máy dùng GPU?
  -> Trên thanh công cụ hãy chọn: `Edit -> Notebook settings or Runtime -> Change runtime type and select GPU as Hardware accelerator.`
  # *LAB2*
 ## Answer:
 

  

