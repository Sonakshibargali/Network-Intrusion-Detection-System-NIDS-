# How to Run NIDS Security Audit Project

## 1. Start the Backend
1.  Open PowerShell.
2.  Run these commands:
    ```powershell
    cd "C:\Users\barga\OneDrive\Documents\Desktop\Security audit project\Security audit project\backend"
    python -m uvicorn app_main:app --reload
    ```
    *Keep this window open.*

## 2. Start the Frontend
1.  Open a **new** PowerShell window.
2.  Run these commands:
    ```powershell
    cd "C:\Users\barga\OneDrive\Documents\Desktop\Security audit project\Security audit project\frontend"
    python -m http.server 8080
    ```
    *Keep this window open too.*

## 3. Open in Browser
*   **Login Page**: [http://localhost:8080/login.html](http://localhost:8080/login.html)
*   **Credentials**:
    *   Username: `sonakshi`
    *   Password: `1234`

## Troubleshooting
*   If you see "Internal Server Error", check the backend terminal for details.
*   If pages don't load, make sure both black terminal windows are still open.
