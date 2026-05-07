# Positive WhatsApp replies export

CSV-ul conține pentru fiecare contact mesajul cel mai relevant pozitiv găsit în conversația WhatsApp Business.

Regulă folosită:
- dacă există autoresponder + mesaj ulterior pozitiv, este ales mesajul ulterior pozitiv
- dacă există doar autoresponder, rămâne autoresponderul
- răspunsurile clar negative sunt excluse

Coloane:
- `internal_contact_name`
- `whatsapp_chat_name`
- `whatsapp_client_reply`
- `reply_type`
- `phone`
