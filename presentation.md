# Electricity Sales Portal

s. Accessible at:  
🔗 [https://magetsi.escom.mw:3006/](https://magetsi.escom.mw:3006/)

---

## Admin Credentials

| Password | Vendor Name         | Username           |
|----------|---------------------|--------------------|
| 52902    | NBS Bank            | NBSBANK            |
| 52901    | First Merchant Bank | FIRSTMERCHANTBANK  |
| 52904    | FDH Bank            | FDHBANK            |
| 59215    | AIRTEL              | AIRTEL             |
| 52918    | MYBUCKS             | MYBUCKS            |
| 52916    | NBM in Malawi       | NBMINMALAWI        |
| 52913    | TNM MPAMBA LTD      | TNMMPAMBALTD       |
| 52906    | Standard Bank       | STANDARDBANK       |
| 52903    | MALSWITCH           | MALSWITCH          |

---

## Workflow Demonstration

### 1. Airtel Vendor Flow
1. **Login**  
   - Use credentials: `AIRTEL/59215`
   
2. **Dashboard**  
   - Vendor-specific transaction overview
   - Real-time settlement status
   - Revenue analytics by service type

3. **User Management**  
   - Create new user:  
     ```
     Username: airtel_agent_01
     Password: [secure_password]
     Role: Transaction Approver
     ```
   - Login with new user credentials
   - Retrieve authentication token via API:  
     `POST /api/v1/auth/token`

4. **Logout**  
   - Terminate session via top-right menu

---

### 2. NBS Bank Reconciliation
1. **Login**  
   - Use credentials: `NBSBANK/52902`

2. **User Management**  
   - View user list (19 registered users)
   - Filter by:  
     - Active status
     - Last login date
     - Permission level

3. **Reconciliation**  
   - Daily transaction matching
   - Discrepancy reporting
   - Automated settlement file generation

---

## Key Features
- 🔐 Role-based access control
- 📊 Customizable vendor dashboards
- ⚡ Real-time transaction monitoring
- 📁 Automated report generation
- 🔄 Bulk reconciliation tools

---

## Support
For technical assistance, contact:  
📧 support@magetsi.mw  
☎ +265 123 456 789