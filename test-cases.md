# 🏦 Kapital Bank – Filial Axtarışı Test Cases

**Test Obyekti:** Kapital Bank veb saytı  
**URL:** https://www.kapitalbank.az/locations  
**Test Növü:** Manual Testing  

---

## 📌 Layihə Haqqında

Bu sənəd Kapital Bank veb saytında Filial, ATM və digər xidmət nöqtələrinin axtarışı funksionallığının test ssenarilərini əhatə edir.

Testlər iki hissəyə bölünmüşdür:
- ✅ Pozitiv Testlər
- ❌ Neqativ Testlər

---

# ✅ Pozitiv Test Cases

| Test ID | Funksionallıq | Test Növü | Steps | Expected Result |
|----------|---------------|------------|--------|----------------|
| TC_FA_01 | Filial Axtarışı | Pozitiv | 1. Sayta daxil ol <br> 2. "Xidmət Şöbəsi" klik et <br> 3. "Filial" seç <br> 4. "Bakı" seç | Bakı filialları düzgün göstərilir |
| TC_FA_02 | Filial Axtarışı | Pozitiv | 1. Sayta daxil ol <br> 2. "Xidmət Şöbəsi" klik et <br> 3. "Filial" seç <br> 4. "Gəncə" seç | Gəncə filialları düzgün göstərilir |
| TC_FA_03 | ATM Axtarışı | Pozitiv | 1. Sayta daxil ol <br> 2. "Xidmət Şöbəsi" klik et <br> 3. "Bankomat" seç <br> 4. "Bakı" seç | Bakı ATM siyahısı göstərilir |
| TC_FA_04 | Ödəniş Terminalı | Pozitiv | 1. Sayta daxil ol <br> 2. "Xidmət Şöbəsi" klik et <br> 3. "Ödəniş Terminalı" seç <br> 4. "Gəncə" seç | Gəncə ödəniş terminalları göstərilir |
| TC_FA_05 | Rəqəmsal Mərkəz | Pozitiv | 1. Sayta daxil ol <br> 2. "Xidmət Şöbəsi" klik et <br> 3. "Rəqəmsal Mərkəz" seç <br> 4. "Bakı" seç | Bakı rəqəmsal mərkəzləri göstərilir |

---

# ❌ Neqativ Test Cases

| Test ID | Funksionallıq | Test Növü | Steps | Expected Result |
|----------|---------------|------------|--------|----------------|
| TC_FA_01 | Filial Axtarışı | Neqativ | 1. Sayta daxil ol <br> 2. "Xidmət Şöbəsi" klik et <br> 3. Axtarış sahəsinə "Sumqayıt" yaz <br> 4. Axtar klik et | Nəticə göstərilmir |
| TC_FA_02 | Rəqəmsal Mərkəz | Neqativ | 1. Sayta daxil ol <br> 2. "Xidmət Şöbəsi" klik et <br> 3. "Rəqəmsal Mərkəz" seç <br> 4. Mövcud olmayan şəhər seç | Yalnız mövcud şəhərlər göstərilir |
| TC_FA_03 | Birbank Private | Neqativ | 1. Sayta daxil ol <br> 2. "Xidmət Şöbəsi" klik et <br> 3. "Birbank Private" seç <br> 4. Şəhər siyahısını aç | Yalnız Bakı göstərilir |
| TC_FA_04 | Cash-in ATM | Neqativ | 1. Sayta daxil ol <br> 2. "Xidmət Şöbəsi" klik et <br> 3. "Cash-in" seç <br> 4. "Şəmkir" axtar | Şəmkir siyahıda yoxdur |
| TC_FA_05 | Filial Axtarışı | Neqativ | 1. Sayta daxil ol <br> 2. "Xidmət Şöbəsi" klik et <br> 3. "Filial" seç <br> 4. "@@##" yaz <br> 5. Axtar klik et | Sistem xəta vermir və nəticə göstərmir |

---

# 🛠 Test Mühiti

- Brauzer: Google Chrome  
- Platforma: Web  
- Test Tipi: Manual Functional Testing  

---

# 📊 Nəticə

Pozitiv testlərdə sistem düzgün işləyir.  
Neqativ testlərdə sistem gözlənilən şəkildə məhdudlaşdırma tətbiq edir və sistem xətası baş vermir.
