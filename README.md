چکیده پروژه:

این پروژه به بررسی و پیاده‌سازی مدل‌های یادگیری عمیق برای تقسیم‌بندی تصاویر پزشکی با تمرکز بر تشخیص تومور مغزی می‌پردازد. هدف اصلی این پروژه، استفاده از معماری U-Net برای شناسایی دقیق نواحی توموری در تصاویر MRI مغز است. در این پروژه از دیتاست Medical Segmentation Decathlon (MSD)  که شامل تصاویر پزشکی با برچسب‌های دقیق برای مناطق مختلف است، استفاده شده است.
در طی این فرآیند، مدل U-Net با استفاده از کتابخانه‌های PyTorch، NumPy، TensorBoard و Matplotlib  طراحی و آموزش داده شد. مدل بر روی GPU به مدت حدود ۶ ساعت آموزش دید و برای ارزیابی عملکرد مدل از امتیاز Dice، دقت و حساسیت به‌عنوان معیارهای ارزیابی استفاده شد. 
نتایج نشان داد که مدل U-Net توانایی بالایی در شناسایی و تفکیک نواحی توموری دارد و دقت و حساسیت بالایی در پیش‌بینی‌های خود ارائه می‌دهد. این مدل می‌تواند به عنوان یک ابزار کمکی در بهبود فرآیند تشخیص و درمان بیماری‌های مغزی مورد استفاده قرار گیرد.


### Project Abstract:

This project focuses on the exploration and implementation of deep learning models for medical image segmentation, with a specific emphasis on brain tumor detection. The primary objective of the project is to leverage the U-Net architecture to accurately identify tumor regions in brain MRI images. The Medical Segmentation Decathlon (MSD) dataset, which provides precisely labeled medical images across various regions, was used for this purpose.

Throughout the process, the U-Net model was designed and trained using libraries such as PyTorch, NumPy, TensorBoard, and Matplotlib. The model was trained on a GPU for approximately 6 hours, and its performance was evaluated using Dice score, accuracy, and sensitivity as metrics.

Results demonstrated that the U-Net model possesses a high capability for identifying and segmenting tumor regions, offering high accuracy and sensitivity in its predictions. This model could serve as a supportive tool to improve the diagnostic and treatment processes for brain diseases.
