# forked from mr-dvgiang/Surveillance-Station

# Tuyên bố miễn trừ trách nhiệm

Nghiên cứu này được thực hiện nhằm mục đích nghiên cứu học thuật và trao đổi kỹ thuật, tập trung vào việc tìm hiểu các phương pháp vượt qua cơ chế giới hạn đăng ký bản quyền của phần mềm thương mại.

**Tuyên bố đặc biệt:**

1. Nghiên cứu này chỉ phục vụ cho mục đích nghiên cứu học thuật và học tập kỹ thuật, không được sử dụng cho bất kỳ mục đích trái pháp luật hoặc không phù hợp nào, bao gồm nhưng không giới hạn ở mục đích thương mại, hành vi xâm phạm bản quyền hoặc các hoạt động mang tính phá hoại.
2. Việc công bố kết quả nghiên cứu không đồng nghĩa với việc quảng bá hoặc khuyến khích sử dụng các phương pháp vượt qua cơ chế bảo vệ bản quyền, đồng thời tác giả không chịu trách nhiệm đối với bất kỳ hậu quả hoặc trách nhiệm pháp lý nào phát sinh từ việc sử dụng các phương pháp này.
3. Người sử dụng có trách nhiệm tự đảm bảo rằng mình đã được nhà cung cấp phần mềm cấp phép hợp lệ trước khi thực hiện bất kỳ thao tác nào có liên quan, đồng thời phải tuân thủ mọi quy định pháp luật hiện hành.
4. Tuyên bố miễn trừ trách nhiệm này không áp dụng đối với bất kỳ hành vi vi phạm pháp luật nào. Tác giả không chịu trách nhiệm đối với bất kỳ trách nhiệm pháp lý, tổn thất kinh tế hoặc hậu quả bất lợi nào phát sinh từ việc sử dụng kết quả của nghiên cứu này.

Vui lòng tuân thủ các quy định pháp luật khi sử dụng kết quả nghiên cứu và tự chịu trách nhiệm đối với mọi hành vi của mình.

---

## Tải xuống Surveillance Station

https://archive.synology.com/download/Package/SurveillanceStation

---

## Kích hoạt giấy phép (Crack License)

### Trực tuyến (Online)

```shell
# 1. Thông thường
curl -fsSL https://raw.githubusercontent.com/mr-dvgiang/Surveillance-Station/main/activated.sh | bash

# 2. Sử dụng proxy GitHub (có thể thay bằng proxy khác, lưu ý dấu / ở cuối)
export GPROXY=https://gh-proxy.org/
curl -fsSL ${GPROXY:-}https://raw.githubusercontent.com/mr-dvgiang/Surveillance-Station/main/activated.sh | bash
export GPROXY=

# 3. Sử dụng proxy HTTP(S)/SOCKS5 (hãy thay bằng địa chỉ proxy của bạn)
export CPROXY=http://username:password@192.168.20.1:7890
curl -fsSL -x ${CPROXY:+-x ${CPROXY}} https://raw.githubusercontent.com/mr-dvgiang/Surveillance-Station/main/activated.sh | bash
export CPROXY=
```

### Ngoại tuyến (Offline)

```shell
# 1. Tải xuống:
# https://github.com/mr-dvgiang/Surveillance-Station/archive/refs/heads/main.zip

# 2. Giải nén lên hệ thống DSM của bạn.
unzip Surveillance-Station-main.zip
cd Surveillance-Station-main
chmod +x activated.sh
./activated.sh
```

---

## Khôi phục giấy phép (Restore License)

### Trực tuyến (Online)

```shell
# 1. Thông thường
curl -fsSL https://raw.githubusercontent.com/mr-dvgiang/Surveillance-Station/main/activated.sh | bash -s -- -r

# 2. Sử dụng proxy GitHub (có thể thay bằng proxy khác, lưu ý dấu / ở cuối)
export GPROXY=https://gh-proxy.org/
curl -fsSL ${GPROXY:-}https://raw.githubusercontent.com/mr-dvgiang/Surveillance-Station/main/activated.sh | bash -s -- -r
export GPROXY=

# 3. Sử dụng proxy HTTP(S)/SOCKS5 (hãy thay bằng địa chỉ proxy của bạn)
export CPROXY=http://username:password@192.168.20.1:7890
curl -fsSL ${CPROXY:+-x ${CPROXY}} https://raw.githubusercontent.com/mr-dvgiang/Surveillance-Station/main/activated.sh | bash -s -- -r
export CPROXY=
```

### Ngoại tuyến (Offline)

```shell
# 1. Tải xuống:
# https://github.com/mr-dvgiang/Surveillance-Station/archive/refs/heads/main.zip

# 2. Giải nén lên hệ thống DSM của bạn.
unzip Surveillance-Station-main.zip
cd Surveillance-Station-main
chmod +x activated.sh
./activated.sh -r
```

---
