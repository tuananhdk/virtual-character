# Virtual Character AI - Nền tảng Trò chuyện với Nhân vật AI Đa năng

Virtual Character AI là một ứng dụng web hiện đại (PWA) cho phép bạn trò chuyện với các nhân vật AI được cá nhân hóa. Ứng dụng được thiết kế đặc biệt để hỗ trợ học ngoại ngữ, giải trí và tư vấn thông qua các mô hình ngôn ngữ lớn hàng đầu như Google Gemini và OpenAI GPT.

## 🌟 Tính năng nổi bật

- **Trò chuyện Thông minh**: Kết nối với Google Gemini hoặc OpenAI để có những cuộc đối thoại tự nhiên, sâu sắc.
- **Hỗ trợ Học Ngoại ngữ**: 
    - Tự động sửa lỗi ngữ pháp và chính tả trong tin nhắn của bạn.
    - Gợi ý các phương án trả lời tiếp theo để duy trì cuộc hội thoại.
- **Tương tác bằng Giọng nói**:
    - **Text-to-Speech (TTS)**: Nhân vật có thể đọc tin nhắn bằng nhiều giọng nói khác nhau.
    - **Speech-to-Text (STT)**: Nhập liệu bằng giọng nói thay vì gõ phím.
- **Dịch thuật Đa phương thức**:
    - Dịch câu trả lời của nhân vật sang ngôn ngữ đích.
    - Tùy chọn dịch bằng AI (chất lượng cao) hoặc MyMemory API (miễn phí).
- **Tùy biến Nhân vật**: Tự tạo nhân vật với tính cách, bối cảnh và câu chuyện riêng.
- **Chế độ Ngoại tuyến (PWA)**: Cài đặt ứng dụng lên màn hình chính điện thoại/máy tính và sử dụng mượt mà ngay cả khi kết nối yếu.
- **Đa ngôn ngữ**: Hỗ trợ giao diện Tiếng Việt và Tiếng Anh.
- **Giao diện Hiện đại**: Hỗ trợ Dark Mode, tùy chỉnh Avatar người dùng và quản lý dữ liệu cá nhân.

## 🚀 Hướng dẫn Tạo Project từ Google AI Studio

Để triển khai project này từ Google AI Studio Build, hãy làm theo các bước sau:

1. **Truy cập Google AI Studio**: Mở [Google AI Studio](https://aistudio.google.com/).
2. **Chọn Chế độ Build**: Nhấn vào nút "Build" hoặc "Create New App".
3. **Nhập Prompt Mô tả**: Bạn có thể dán yêu cầu xây dựng ứng dụng chat AI với các tính năng như PWA, TTS/STT, và hỗ trợ học ngoại ngữ.
4. **Cấu hình API Key**:
    - Đảm bảo bạn đã có `GEMINI_API_KEY` từ Google AI Studio.
    - Trong giao diện Build, hệ thống sẽ tự động nhận diện và cấu hình các biến môi trường cần thiết.
5. **Triển khai**: Nhấn "Deploy" để nhận đường dẫn ứng dụng trực tuyến.

## 📖 Hướng dẫn Sử dụng

### 1. Cấu hình Ban đầu
- Khi mở ứng dụng lần đầu, hãy vào mục **Cài đặt (Settings)**.
- Nhập **API Key** của bạn (Gemini hoặc OpenAI).
- Chọn **Ngôn ngữ giao diện** (Tiếng Việt/Tiếng Anh).
- Tùy chỉnh **Avatar** của bạn để cuộc trò chuyện thêm phần cá nhân.

### 2. Bắt đầu Trò chuyện
- Tại **Bảng điều khiển (Dashboard)**, chọn một nhân vật có sẵn hoặc nhấn **"Tạo Nhân vật mới"**.
- Trong màn hình Chat:
    - Nhấn biểu tượng **Micro** để nói thay vì gõ.
    - Nhấn biểu tượng **Loa** để nghe nhân vật nói.
    - Nhấn biểu tượng **Quả địa cầu** để dịch câu trả lời.
    - Nếu là nhân vật dạy học, hãy chú ý phần **"Sửa lỗi Ngữ pháp"** và các nút **"Gợi ý trả lời"**.

### 3. Quản lý Nhân vật
- Bạn có thể chỉnh sửa (Edit) hoặc xóa (Delete) nhân vật bất kỳ lúc nào.
- Khi tạo nhân vật, hãy mô tả kỹ **Tính cách** và **Bối cảnh** để AI phản hồi chính xác nhất.

### 4. Cài đặt Nâng cao
- **Phương thức Dịch**: Chọn "Free" để tiết kiệm hoặc "AI" để có bản dịch chính xác nhất.
- **Giọng nói**: Chọn giọng nói phù hợp cho từng nhân vật trong phần chỉnh sửa nhân vật.

## 🛠 Công nghệ Sử dụng

- **Frontend**: React 19, Vite, TypeScript.
- **Styling**: Tailwind CSS, Framer Motion (cho hiệu ứng).
- **AI**: @google/genai, OpenAI SDK.
- **Internationalization**: i18next.
- **PWA**: vite-plugin-pwa.
- **Icons**: Lucide React.

---
*Phát triển bởi Virtual Character AI Team - Hỗ trợ học tập và sáng tạo không giới hạn.*
