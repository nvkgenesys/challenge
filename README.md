## **Full-Stack Developer Challenge: Inventory Management System**
### **Objective**
Build a basic **Inventory Management System** where users can **add, update, delete, and track inventory items**, manage stock levels, and generate reports.

---

## **Requirements**

### **1. Dashboard (Inventory Overview)**
- Display a **summary of available inventory** with total stock, low-stock alerts, and recently updated items.
- Implement **filters** (e.g., search by category, name, etc.).

### **2. Inventory CRUD Operations**
- Users should be able to:
  - **Create** a new inventory item.
  - **Update** stock levels, price, and supplier details.
  - **Delete** an item.
  - Show a confirmation modal before deleting an item.

### **3. Stock Adjustments**
- Users can adjust stock levels when:
  - **Receiving new stock.**
  - **Recording damaged or lost items.**
- Changes should be logged for auditing purposes.

### **4. Transactions Log (History)**
- Track inventory transactions (e.g., **added stock**, **sold stock**, **damaged stock**).
- Display the transaction history for each item.

### **5. Backend API**
- Use **Next.js API routes** or **Server Actions** to handle CRUD operations securely.
- Implement proper error handling and validation.

### **Bonus (Optional Enhancements)**
- **Pagination** for large inventories.
- **Export inventory reports** (CSV/PDF).

---

## **Tech Stack**
- **Next.js 15** (App Router)
- **TypeScript**
- **Prisma** (PostgreSQL)
- **TailwindCSS**
- **React Hook Form + Zod** (form validation)
- **@tanstack/react-query** (data fetching & caching)

---

## **Evaluation Criteria**
- **Code quality** (clean structure, reusable components).
- **Performance optimizations** (pagination, efficient queries).
- **Database design & API security**.
- **User experience** (intuitive UI, error handling).

---