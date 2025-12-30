<img width="2559" height="1537" alt="image" src="https://github.com/user-attachments/assets/f474fb80-e083-4505-9b27-048956c72aef" />### 📌 Memo API

| 기능 | 메서드 | URL | 요청 본문(JSON) | 설명 |
| :-- | :-- | :-- | :-- | :-- |
| 메모 생성 | POST | `/memos` | `{"text":"메모 내용"}` | 메모를 생성합니다 |
| 메모 전체 조회 | GET | `/memos` | 없음 | 모든 메모 조회 |
| 메모 상세 조회 | GET | `/memos/{id}` | 없음 | 특정 ID의 메모 조회 |
| 메모 수정 | PUT | `/memos/{id}` | `{"text":"수정된 메모"}` | 메모 내용 수정 |
| 메모 삭제 | DELETE | `/memos/{id}` | 없음 | 메모 삭제 |


### 📷 Postman 테스트
"메모 등록"
<img width="700" height="420" alt="image" src="https://github.com/user-attachments/assets/0c6d434f-95cf-4360-960b-89a3b11986fd" />


"메모 상세"
<img width="700" height="420" alt="image" src="https://github.com/user-attachments/assets/3669e0ea-c914-41ed-aef4-9a02aeed1b32" />


"메모 수정"
<img width="700" height="420" alt="image" src="https://github.com/user-attachments/assets/33dca88b-0b1e-49e7-bf65-92fb32fc9dae" />


"메모 삭제"
<img width="700" height="420" alt="image" src="https://github.com/user-attachments/assets/22894083-f3a6-4806-9eff-4b43b4ad4db2" />
