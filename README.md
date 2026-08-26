# Giá đỡ bầu rễ bonsai thuỷ sinh

Một cây thân gỗ nhỏ đã rửa sạch bầu đất, trồng thuỷ sinh trong hồ kính, bầu rễ thả
rơi tự do chạm đáy. Bộ này **móc lên thành hồ** và đỡ bầu rễ bằng một cái **phễu
côn**, chỉnh được độ sâu cổ rễ.

**[Xem mô hình 3D →](viewer/index.html)** ·
[Phễu côn — viewer tham số](viewer/v3-pheu-con-linh-hoat.html) ·
[Bốn phương án móc thành](viewer/v2-chon-phuong-an-moc-thanh.html)

---

## ĐO BẦU RỄ TRƯỚC — nó quyết định cỡ phễu

Đo **bề ngang bầu rễ ở chỗ dưới cổ rễ 12 mm**. Con số đó chọn cỡ phễu:

| Cỡ | Bầu rễ | Phễu | Miếng chặn |
|---|---|---|---|
| **S** | Ø18–32 mm | `funnel-S.stl` · 12,2 g · 1h16 | `gate-S.stl` · 1,1 g |
| **M** | Ø26–44 mm | `funnel-M.stl` · 15,1 g · 1h33 | `gate-M.stl` · 1,5 g |
| **L** | Ø36–64 mm | `funnel-L.stl` · 23,2 g · 2h19 | `gate-L.stl` · 2,9 g |

Chưa chắc cỡ nào thì **in cả hai cỡ kề nhau rồi ướm** — phễu chỉ 12–23 g.

Vành đỡ chỉ có chỗ tựa nếu bầu **nở ra nhanh ngay dưới cổ rễ**. Bầu nở chậm thì
vành phải tụt sâu mới bắt được vai, và bộ này không dùng được — phải đỡ cây bằng
cách khác.

---

## Chi tiết

| File | Là cái gì | Nhựa | Thời gian | Số bản |
|---|---|---|---|---|
| `stl/hook-arm.stl` | Tay móc lên thành hồ. **Dùng chung cho cả ba cỡ**, không đổi một mm nào | 14,6 g | 1h47 | 1 |
| `stl/funnel-<cỡ>.stl` | Phễu côn đỡ bầu rễ. Mang **dấu bản quyền** khắc chìm uốn theo vành khuyên, mặt dưới | 12–23 g | 1h16–2h19 | 1 |
| `stl/gate-<cỡ>.stl` | Miếng chặn hình chữ C giữ bầu rễ khỏi tuột ngang | 1–3 g | ~15 phút | **3–4** |

**In dư 3–4 miếng chặn.** Chúng nhỏ, và mất một cái thì bầu rễ tuột ngang qua
miệng chữ C.

### Cần mua thêm

**1 bu lông M3 × 30 INOX A2 + đai ốc.** Không dùng thép đen — ngâm nước vài tuần là
rỉ, và rỉ sắt trong hồ kín thì không rửa lại được.

---

## Cột chỉnh được độ sâu

Cột vươn lên 62 mm; cổ rễ chỉnh được trong khoảng **−10 đến +38 mm** so với mép
kính. Cây thuỷ sinh gần như luôn thấp hơn thành hồ, nên khoảng chỉnh này là để kéo
cây **lên** cho tán nhô khỏi mặt nước, không phải để dìm xuống.

---

## Vật liệu — PETG, không có ngoại lệ

Ngâm nước **vĩnh viễn**, và có hai lý do riêng nữa:

1. **Giá móc chịu tải tĩnh liên tục nhiều năm.** PLA creep (biến dạng nguội) dưới
   tải tĩnh ở nhiệt độ phòng — cột vồng dần thì vành tụt xuống, cổ rễ ngập trở lại,
   và không ai thấy cho tới lúc cây có dấu hiệu.
2. **Vành đỡ trực tiếp vào rễ sống.** Nhựa giòn vỡ ra thành mảnh sắc ngay trong bộ rễ.

PETG **trong hoặc trắng nguyên sinh**. Không dùng nhựa tái chế hoặc có phụ gia màu lạ.

---

## Cài đặt in

Vòi 0,4 · lớp 0,2 · **không support** · đã ở đúng tư thế in trong file.

Ba mảnh rời chính là **vì** không mảnh nào cần support:

| Chi tiết | Tư thế | Vì sao |
|---|---|---|
| `hook-arm` | **nằm** — biên dạng xuống bàn | Lăng trụ đùn theo một trục, mọi mặt bên là vách đứng, dốc 0°. Ba lỗ bu lông thành lỗ **đứng** (tròn nhất). Lưỡi gà đàn hồi nằm ngay trong biên dạng nên nó cũng là vách đứng |
| `funnel-<cỡ>` | **đứng**, vành khuyên đáy bám bàn | Mặt trong hướng lên (đó là mặt tựa), mặt ngoài dốc 38° so phương đứng — dưới ngưỡng 45°, còn 7° dự phòng |
| `gate-<cỡ>` | nằm | Tấm nêm, dốc 0° |

**Phễu cần brim.** Nó đứng trên một vành khuyên rộng chỉ 5 mm mà cao 50 mm kể cả
nĩa — dễ đổ.

> Phương án "phễu bậc thang" đã thử và **đã loại**: mỗi bậc để lại một vành khuyên
> nằm ngang hướng xuống, liên thông 360° — đo được 415 mm² ngay cả với bậc hẹp 2 mm,
> gấp đôi ngưỡng an toàn.

---

## Trạng thái

⚠️ **Chưa in thật lần nào**, và quan trọng hơn: **chưa có số đo nào từ vật thật.**
Mọi tham số hiện tại đọc từ ảnh (±10%) và mượn kích thước hồ từ một dự án khác.

Đo bầu rễ của cây bạn trước, đối chiếu với bảng cỡ ở trên, rồi mới in.

---

## Giấy phép

[CC BY-NC-SA 4.0](LICENSE) — dùng tự do phi thương mại, ghi nguồn
`github.com/doducminh`, bản sửa phát hành cùng giấy phép.
