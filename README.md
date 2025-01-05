# BMR Calculator

### คำนวณ BMR (Basal Metabolic Rate) :
- ถ้าเพศเป็น ชาย (male) จะใช้สูตร BMR สำหรับผู้ชาย :
> 𝐵𝑀𝑅=88.362+(13.397×weight)+(4.799×height)−(5.677×age)
- ถ้าเพศเป็น หญิง (female) จะใช้สูตร BMR สำหรับผู้หญิง :
> 𝐵𝑀𝑅=447.593+(9.247×weight)+(3.098×height)−(4.330×age)

# SteamTurbine

### ⚠️ Input Fields :
- อัตราการไหลของไอน้ำ (dot m) : ผู้ใช้กรอกอัตราการไหลของไอน้ำในหน่วย kg/s
- ความหนาแน่นของไอน้ำก่อนเทอร์ไบน์ (h1) : ความหนาแน่นของไอน้ำที่สถานะก่อน (kJ/kg)
- ความหนาแน่นของไอน้ำหลังเทอร์ไบน์ (h2) : ความหนาแน่นของไอน้ำที่สถานะหลัง (kJ/kg)
- Result : ผลลัพธ์ของการคำนวณจะถูกแสดงในช่อง "กำลังไฟฟ้าที่ผลิตได้ (P) (W)"

### การคำนวณ :
> ใช้สูตร 𝑃 = 𝑚˙× ( ℎ1− ℎ2 )
- ซึ่งการคำนวณจะใช้ค่าจาก input และผลลัพธ์จะได้ในหน่วย Watt (W)
- ผลลัพธ์ที่ได้จะถูกแปลงจาก kiloJoule เป็น Joule โดยการคูณด้วย 1000
