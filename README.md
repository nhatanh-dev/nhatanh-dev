# Nguyễn Phạm Nhật Anh

**Backend Developer · .NET** — Ho Chi Minh City, Vietnam

[Portfolio](https://anhnpn.vercel.app) · [LinkedIn](https://linkedin.com/in/anhnguyen2505) · [Email](mailto:anhnguyenphamnhat@gmail.com)

```csharp
var developer = new Developer
{
    Name      = "Nguyễn Phạm Nhật Anh",
    Role      = "Backend Developer",
    Education = "Software Engineering @ FPT University HCMC (06/2027)",
    Stack     = ["C#", "ASP.NET Core", "PostgreSQL", "SQL Server", "RabbitMQ"],
    FocusOn   = ["Payments & billing", "Realtime (SignalR)", "Concurrency", "Async processing"],
    Currently = "Building Livento – AI Livestream Studio"
};
```

## 👋 Giới thiệu

Sinh viên năm cuối Kỹ thuật Phần mềm, định hướng Backend. Kinh nghiệm chính qua các dự án nhóm: tích hợp thanh toán & billing (VNPay trong 3 dự án), realtime với SignalR, kiểm soát truy cập đồng thời và xử lý bất đồng bộ (RabbitMQ, BackgroundService, transactional outbox). Có làm thêm frontend với **React** và triển khai bằng **Docker / AWS**.

> 🚀 **Hiện tại:** cùng team khởi nghiệp phát triển **[Livento – AI Livestream Studio](https://studio.livento.id.vn/)**, phụ trách nghiệp vụ và luồng xử lý của sản phẩm.

## 🧩 Dự án nổi bật

| Dự án | Đóng góp chính |
|:--|:--|
| 🚤 **[Smart Waterbus](https://github.com/minhvuong0909/waterbus-system)**<br/><sub>Đặt vé tàu buýt đường sông theo chặng</sub><br/>`.NET 8` `SQL Server` `SignalR` | Commercial backend: checkout, thanh toán & hoàn tiền VNPay (verify IPN, đối soát giao dịch); chống race condition bằng SQL Server app lock + `RowVersion`; transactional email outbox |
| 📚 **[InsightVault AI](https://github.com/tuankiet18-dev/InsightVault-AI)**<br/><sub>Không gian tri thức cho team với RAG chat</sub><br/>`ASP.NET Core` `pgvector` `RabbitMQ` | Thiết kế kiến trúc backend; xử lý job AI bất đồng bộ qua RabbitMQ; billing & credit theo workspace (VNPay/PayOS); CI và deploy EC2 |
| 🛡️ **[SmartInvoice Shield](https://github.com/tuankiet18-dev/SMARTINVOICE-SHIELD)**<br/><sub>SaaS quản lý hóa đơn điện tử, AI/OCR</sub><br/>`.NET 9` `PostgreSQL` `AWS` | Thanh toán VNPay & quota theo gói subscription; quản lý hóa đơn, audit log; phân quyền RBAC; tích hợp pipeline OCR |
| ⚡ **[EVoltStation](https://github.com/nhatanh-dev/EVStation-API)** · [demo](https://evoltstation.io.vn)<br/><sub>Quản lý trạm sạc xe điện</sub><br/>`.NET 9` `SignalR` `SQL Server` | Luồng phiên sạc realtime qua SignalR; tính phí chiếm chỗ & xử lý vi phạm bằng background job; luồng khách vãng lai |

## 🛠️ Tech stack

<p>
<img src="https://skillicons.dev/icons?i=cs,dotnet,postgres,rabbitmq,aws,docker,githubactions,react,ts,tailwind&theme=dark" alt="tech stack"/>
</p>

- **Backend:** C#, ASP.NET Core, Entity Framework Core, SignalR, REST API, BackgroundService
- **Data & Messaging:** PostgreSQL (pgvector), SQL Server, RabbitMQ
- **Cloud & DevOps:** AWS (EC2, RDS, S3, Cognito), Docker, GitHub Actions
- **Frontend:** React, TypeScript, Tailwind CSS

## 🎮 Game & AI sáng tạo

<a href="https://banyan-base-airisers.netlify.app/"><img src="assets/banyan-base.png" width="420" alt="Banyan Base"/></a>

- **[Banyan Base: Cuội & Moxi](https://banyan-base-airisers.netlify.app/)**: game cho NASA Space Apps Challenge 2026 (team AI RISERS); phụ trách 3D asset, dựng bằng công cụ AI
- **[Flood Route](https://github.com/nhatanh-dev/flood-route)**: game giải đố giải cứu lũ theo lượt, làm bằng Unity

## 🏅 Hoạt động & thành tích

- 🎓 **Sinh viên Giỏi** 4 học kỳ, FPT University
- ☁️ **AWS First Cloud AI Journey (FCAJ)**: chương trình thực hành AWS · [workshop](https://github.com/nhatanh-dev/FCAJ_Workshop)
- 🚀 **NASA Space Apps Challenge 2026**, team AI RISERS
- 📜 Chứng chỉ Coursera (Software Development Lifecycle, …): xem tại [portfolio](https://anhnpn.vercel.app)

<details>
<summary><b>🇬🇧 English version</b></summary>

<br/>

Final-year Software Engineering student at **FPT University HCMC** (expected 06/2027), aiming for a **Backend Developer** role with **C# / ASP.NET Core**, **PostgreSQL** and **SQL Server**.

Main experience from team projects: payments & billing (VNPay in three projects), realtime with SignalR, concurrency control and async processing (RabbitMQ, BackgroundService, transactional outbox). Also builds frontends with **React** and deploys with **Docker / AWS**.

**Currently** co-building **[Livento – AI Livestream Studio](https://studio.livento.id.vn/)** with a startup team, owning business logic and product workflows.

| Project | Key contributions |
|:--|:--|
| **Smart Waterbus** | Commercial backend: checkout, VNPay payment & refund (IPN verification, reconciliation), race-condition fixes with SQL Server app locks + `RowVersion`, transactional email outbox |
| **InsightVault AI** | Backend architecture, RabbitMQ-based AI job processing, workspace billing & credits (VNPay/PayOS), CI and EC2 deployment |
| **SmartInvoice Shield** | VNPay with subscription quotas, invoice management & audit log, RBAC, OCR pipeline integration |
| **EVoltStation** | Realtime charging-session flow over SignalR, overstay fees & rule enforcement via background jobs, walk-in customer flow |

**Activities:** Excellent Student award (4 semesters) · AWS First Cloud AI Journey · NASA Space Apps Challenge 2026 · Coursera specializations

</details>

