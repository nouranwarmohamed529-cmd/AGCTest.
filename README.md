# AGCTest.
# Women Equality & Safety API

## 📌 Problem
Women across the world face **safety concerns** (harassment, unsafe public transport, poorly lit areas) and **inequality** (workplace discrimination, underrepresentation in leadership, pay gaps).  

This API allows people to **report** and **track** such issues to support advocacy, policy-making, and awareness.

---

## 🚀 Endpoints

### 1. POST `/reports` → Submit a new report
- **Fields:** `id`, `city`, `category`, `description`, `reporter (optional)`
- **Example Request:**
```json
{
  "id": 1,
  "city": "Cairo" "Alexandria",
  "category": "Workplace Inequality",
  "description": "Women in this company are paid less than men.",
  "reporter": "Anonymous"
}
