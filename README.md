# ai-builders-orientation
Lesson 0 - Orientation

## แบบฝึกหัด Lesson 0

1. Fork repository https://github.com/vistec-AI/ai-builders-orientation ไปใน github ของตัวเอง

2. Clone repository ที่ fork ไป ด้วยคำสั่งต่อไปนี้ (สมมุติว่า username ของคุณคือ `yourgithubuser`)

```
git clone https://github.com/yourgithubuser/ai-builders-orientation

```
3. หาไฟล์ `aib_2021/yoursurname_proposal.ipynb` แล้ว copy มาเป็นนามสกุลของตัวเอง เช่น `aib_2021/chan-o-cha_proposal.ipynb`)

4. เติมคำตอบในไฟล์ของตัวเองใน folder `aib_2021` เช่น `aib_2021/chan-o-cha_proposal.ipynb`

5. เพิ่มไฟล์เข้าไปใน git staging ด้วยคำสั่ง (สมมุติว่าไฟล์ของคุณคือ `aib_2021/chan-o-cha_proposal.ipynb`)

```
git add aib_2021/chan-o-cha_proposal.ipynb
```

6. ดูว่าไฟล์ถูกเพิ่มเข้าไปใน staging หรือยังด้วยคำสั่ง

```
git status
```

7. commit ไฟล์ใน staging ด้วยคำสั่ง ใส่ comment ไปด้วย เช่น `add aib_2021/chan-o-cha_proposal.ipynb`

```
git commit -m 'aib_2021/chan-o-cha_proposal.ipynb'
```

8. push commit ขึ้นไปใน branch `main` ของ repository ที่เรา fork มา

```
git push origin main
```

9. กด Pull Request ไปที่ repository หลัก (https://github.com/vistec-AI/ai-builders-orientation) แล้วรอให้ทีมงาน merge
