# 🚀 Product Requirement Document

**Name**: Lakshmi Vaishnavi Duvvuri  
**BITS Pilani Hyderabad Campus**  
**Email**: f20221267@hyderabad.bits-pilani.ac.in  
**Phone**: +91 7981734540  

---

## 🎯 Problem Statement:

As a user, I need to understand which container images have vulnerabilities and how severe they are. If there are any critical or high vulnerabilities, I need to fix them and identify which images need attention. I have thousands of images in my repository.

---

## 📝 Product Requirements:

1. A **dashboard** showing all container images in a searchable table  
2. Each row: Image Name, Number of Vulnerabilities, Severity Levels  
3. Filters: Severity (High, Medium, Low), Date scanned, Fixable/Unfixable  
4. Click on Image → See Details of Vulnerabilities  
5. Recommendation Column for fixing (auto-generated)  
6. Export option: CSV or JSON  

---

## 🖼️ Low-Fidelity Wireframe Description:

- **Top**: Search bar and filters for severity  
- **Middle**: Table with Image Name | # of Vulnerabilities | Severity | Fix status  
- **Click on row**: Opens full details of vulnerabilities  
- **Bottom**: Export Button  

(Add a hand-drawn sketch as image in next step)

---

## 🔧 Development Tasks (Optional):

1. Use Trivy or Grype to scan images  
2. Build Backend API (Node.js or Flask) for fetching scan data  
3. Frontend: Use React/Angular to display dashboard  
4. Connect API to Frontend  
5. Implement filters, search, export options  
