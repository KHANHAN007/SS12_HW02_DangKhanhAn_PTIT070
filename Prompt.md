# Prompt tạo tài liệu SRS cho tính năng eKYC

## Vai trò

Bạn là Senior Business Analyst kiêm Solution Architect với hơn 10 năm kinh nghiệm trong lĩnh vực Ngân hàng số.

Nhiệm vụ của bạn là tạo tài liệu Software Requirements Specification (SRS) theo chuẩn IEEE 830 cho tính năng eKYC của ABC Bank.

---

## Bối cảnh

ABC Bank triển khai chức năng eKYC cho phép khách hàng mở tài khoản trực tuyến.

Quy trình gồm:

- Người dùng đăng ký tài khoản.
- Upload ảnh mặt trước CCCD.
- Upload ảnh mặt sau CCCD.
- OCR đọc thông tin.
- Chụp ảnh Selfie.
- Liveness Detection.
- So sánh khuôn mặt.
- Nếu hợp lệ thì kích hoạt tài khoản.
- Nếu thất bại cho phép thực hiện lại tối đa 3 lần.

---

## Yêu cầu tài liệu

Sinh tài liệu SRS theo chuẩn IEEE gồm:

# 1. Introduction

- Purpose
- Scope
- Definitions
- Acronyms
- References

# 2. Overall Description

Bao gồm:

- Product Perspective
- Product Functions
- User Classes
- Operating Environment
- Design Constraints
- Assumptions

# 3. Specific Functional Requirements

Mỗi chức năng cần có:

- Requirement ID
- Description
- Actors
- Preconditions
- Main Flow
- Alternative Flow
- Post Conditions
- Business Rules

Bao gồm các module:

FR-01 Đăng ký tài khoản

FR-02 Upload CCCD

FR-03 OCR

FR-04 Face Verification

FR-05 Liveness Detection

FR-06 Activate Account

# 4. Non Functional Requirements

Bao gồm:

Security

Performance

Availability

Reliability

Scalability

Audit Log

Backup

# 5. Visual Diagram

Sinh Use Case Diagram bằng Mermaid.

Ngoài ra sinh thêm Activity Diagram bằng Mermaid.

Sử dụng Markdown.

Không giải thích.

Chỉ sinh tài liệu.
