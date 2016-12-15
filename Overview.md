# Overview about Kubernetes
## Kubernetes là gì
- Kubernetes là hệ thống mã nguồn mở để tự động deploy, scale và quản lý các app chạy trên container.
- Nó nhóm các container lại vào trong 1 logic unit để dễ dàng quản lý và discovery.
- Bất kể test trên local hay run trên global enterprise, kubernetes vẫn dễ dàng grow mở rộng app của bạn ngay lập tức bât kể độ phức tạp của app.
- Run anywhere: hybrid, or public cloud infrastructure.

## Kubernetes Features
- Automatic binpacking: Tự động place container dựa trên yêu cầu về tài nguyên và các hạn chế #.
- Self-healing: Restart container failed, replaces và reschedules container khi node die, kill container nếu không respond, và không advertise
chúng tới client đến khi sẵn sàng sử dụng.
- Horizontal scaling: scale up and down app của bạn với command đơn giản, với UI hoặc tự động dựa trên CPU usage.
- Service discovery and load balancing: Không cần modify app của bạn sử dụng 1 cơ chế discovery service mà không biết.Kubernetes cung cấp cho
container các IP riêng của nó và 1 DNS cho 1 set các containers và có tể load-balance giữa chúng.
- 
