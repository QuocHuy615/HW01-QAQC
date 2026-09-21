# Sơ đồ tư duy dạng Danh sách phân cấp (Markdown)

## Vai trò QA/QC & Ma trận Kỹ năng (2026+)

## 1. Phân biệt QA & QC (Theo chuẩn ISTQB)

#### QA (Quality Assurance - Đảm bảo chất lượng)

- **Mục tiêu:** Hướng quy trình (Process-oriented).
- **Trọng tâm:** Phòng ngừa lỗi (Defect prevention).
- **Phạm vi:** Xuyên suốt toàn bộ vòng đời phát triển phần mềm (SDLC).

#### QC (Quality Control - Kiểm soát chất lượng / Testing)

- **Mục tiêu:** Hướng sản phẩm (Product-oriented).
- **Trọng tâm:** Phát hiện lỗi (Defect detection).
- **Phạm vi:** Chủ yếu tập trung vào các giai đoạn kiểm thử sau khi mã nguồn đã được viết.

## 2. Các vai trò Truyền thống & Hiện đại

#### Test Manager / Test Lead

- **Kỹ năng nền tảng:** Lập kế hoạch kiểm thử, Quản lý rủi ro, Ước lượng nỗ lực, ISTQB Advanced.
- **Kỹ năng công cụ & AI:** Jira/Zephyr, Sử dụng GenAI để phân tích rủi ro & dự phóng tiến độ, AI-driven dashboards.
- **Kỹ năng mềm & Quy trình:** Lãnh đạo, Đàm phán, Quản lý SDLC/Agile.

#### QA Engineer (Process QA)

- **Kỹ năng nền tảng:** Thiết kế quy trình, CMMI, ISO 9001, Internal Audit.
- **Kỹ năng công cụ & AI:** QMS Systems, Process Mining tools tích hợp AI để tối ưu workflow.
- **Kỹ năng mềm & Quy trình:** Phân tích hệ thống, Giải quyết vấn đề, Tư duy phản biện.

#### QC / Manual Tester

- **Kỹ năng nền tảng:** Kỹ thuật thiết kế Test Case (Black-box, White-box, Experience-based), Phân tích nghiệp vụ.
- **Kỹ năng công cụ & AI:** Postman, TestRail, AI Copilots (tạo test data, sinh draft test cases từ user story).
- **Kỹ năng mềm & Quy trình:** Chú ý tiểu tiết, Giao tiếp báo cáo lỗi, Scrum/Kanban.

#### Automation Test Engineer

- **Kỹ năng nền tảng:** Lập trình (Java, Python, TS), Kiến trúc Framework (POM), CI/CD pipeline.
- **Kỹ năng công cụ & AI:** Playwright, Selenium, Appium, Các công cụ tự phục hồi mã kiểm thử (AI Self-healing), AI code generators.
- **Kỹ năng mềm & Quy trình:** Tư duy logic, Clean Code, Agile Testing.

#### Performance / Security Tester (Niche Roles)

- **Kỹ năng nền tảng:** Load/Stress testing (JMeter), OWASP Top 10, Pen-testing, Phân tích kiến trúc.
- **Kỹ năng công cụ & AI:** Burp Suite, AI-driven Threat Intelligence, AI Load Modeling.
- **Kỹ năng mềm & Quy trình:** Phân tích dữ liệu lớn, Đánh giá rủi ro bảo mật.

## 3. Các vai trò Mới Tích hợp AI (2026+)

#### AI Test Engineer

- **Kỹ năng nền tảng:** Hiểu biết về thuật toán Machine Learning, Data Science cơ bản, Model evaluation metrics (Precision, Recall).
- **Kỹ năng công cụ & AI:** MLOps tools, Python (TensorFlow, PyTorch), AI Test frameworks.
- **Kỹ năng mềm & Quy trình:** Tư duy thống kê, Quản lý vòng đời dữ liệu.

#### LLM Quality Evaluator

- **Kỹ năng nền tảng:** Đánh giá RAG (Retrieval-Augmented Generation), Kiểm thử tính thiên kiến (Bias), ảo giác (Hallucination) và Kiểm thử an toàn đối kháng (Prompt Injection, Jailbreak)
- **Kỹ năng công cụ & AI:** LangSmith, TruLens, DeepEval, Các công cụ benchmark LLM.
- **Kỹ năng mềm & Quy trình:** Ngôn ngữ học, Phân tích ngữ cảnh, Đạo đức AI (AI Ethics).

#### Prompt Engineer for Testing

- **Kỹ năng nền tảng:** Kỹ thuật Prompting (Few-shot, Chain-of-Thought), Tối ưu hóa truy vấn để sinh test case/test data đa dạng.
- **Kỹ năng công cụ & AI:** Giao diện API của các mô hình LLM (Gemini, GPT, Claude), Prompt Management platforms.
- **Kỹ năng mềm & Quy trình:** Sáng tạo, Tư duy ngôn ngữ, Thích ứng nhanh.

## 4. Quy trình hoạt động kiểm thử (Test Activities - ISTQB V4.0)

- **Nguyên tắc thực thi:** Áp dụng Whole Team Approach (Toàn bộ thành viên Dev, QA, QC, PO cùng chia sẻ trách nhiệm trong mọi hoạt động từ Phân tích đến Thực thi, không gán cứng rào cản vai trò).

#### Test Planning (Lập kế hoạch)

#### Test Monitoring & Control (Giám sát & Kiểm soát)

#### Test Analysis (Phân tích)

#### Test Design (Thiết kế)

#### Test Implementation (Thực thi thiết lập)

- **Nhiệm vụ cốt lõi:** Tham gia QC (Xây dựng Test Procedures, Test Suites và chuẩn bị Test Data).

#### Test Execution (Thực thi chạy test)

#### Test Completion (Đóng luồng kiểm thử)