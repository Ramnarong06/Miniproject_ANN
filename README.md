## Project นี้เป็นส่วนหนึ่งของรายวิชา ARTIFICIAL NEURAL NETWORKS
เป็นงานเกี่ยวกับการ จำแนกประเภทภาพ (Image Classification) ผ่านการใช้หลักการ Convolutional Neural Network (CNN) ในการเรียนรู้และแบ่งภาพแมงกะพรุนออกเป็น 6 ประเภท (classes)
โดยปรับขนาด filter ตามความเหมาะสมของผลลัพธ์ให้ออกมาใกล้เคียงที่สุด         
## หลักการการจำแนกด้วย CNN
- Convolutional Layer: ตรวจจับลักษณะเด่นของภาพ เช่น ขอบ สี รูปทรง โดยใช้ Filter  
- Activation Function (ReLU): เพิ่มความไม่เป็นเชิงเส้น (non-linearity) เพื่อให้โมเดลเรียนรู้ได้ซับซ้อน  
- Convolutional Layer: ตรวจจับลักษณะเด่นของภาพ    
- Pooling Layer (MaxPooling): ลดขนาดภาพ เพื่อลดจำนวนพารามิเตอร์ เพื่อเพิ่มความทนทานต่อการเปลี่ยนแปลง  
- Flatten Layer: แปลงจาก 2D matrix เป็น 1D vector เพื่อนำเข้า Dense Layer  
- Dropout Layer: ป้องกัน overfitting โดยสุ่มปิดบาง neuron  
