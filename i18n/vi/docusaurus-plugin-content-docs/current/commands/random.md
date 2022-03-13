---
sidebar_position: 4
---

# Ngẫu nhiên

Trong tài liệu này, chúng tôi sẽ sử dụng prefix mặc định là `e`.

## COINFLIP

> Tung một đồng xu
>
> #### Cú pháp
>
> `ecoinflip`
>
> #### Thay thế
>
> `cf` `coin` `flip` `xu` `lat` `latdongxu` `latxu`
>
> #### Ví dụ
>
> `ecoinflip`

## DICE

> Tung một số con xúc xắc
>
> #### Cú pháp
>
> `edice [number of faces in first dice] [number of faces in second dice] ... [number of faces in nth dice]`
>
> Nếu bạn không cung cấp số mặt của một xúc xắc nào, mặc định sẽ là một viên 6 mặt
>
> #### Thay thế
>
> `xucxac` `xingau` `doxingau` `tungxucxac` `xn` `xx`
>
> #### Ví dụ
>
> `edice`
>
> `edice 6`
>
> `edice 10 12 20`

## LOREMIPSUM

> Tạo ra một đoạn Dummy Text
>
> #### Cú pháp
>
> `eloremipsum <DD/MM>`
>
> #### Thay thế
>
> `li` `lorem` `ipsum` `dummy`
>
> #### Ví dụ
>
> `eloremipsum`

## PASSWORD

> Tạo ra một mật khẩu mạnh
>
> #### Cú pháp
>
> `epassword <length>`
>
> Độ dài phải là một số nguyên dương lớn hơn hoặc bằng 8 và nhỏ hơn hoặc bằng 100
>
> #### Thay thế
>
> `pass` `mk` `passgen` `autopass` `taomk` `matkhau`
>
> #### Ví dụ
>
> `epassword 12`

## PICK

> Chọn một lựa chọn ra khỏi một danh sách
>
> #### Cú pháp
>
> `epick <first option>,<second option>,[third option],[forth option],...`
>
> #### Thay thế
>
> `choose` `chon`
>
> #### Ví dụ
>
> `epick wheat,bot,hello`

## RAND

> Chọn một số ngẫu nhiên trong đoạn
>
> #### Cú pháp
>
> `erand [min boundary (max)] [max boundary]`
>
> Nếu bạn không hề nhập vào một thông tin gì, đoạn mặc định sẽ là [1, 100].
>
> Nếu bạn nhập vào một con số, đoạn được chọn sẽ là [1, số bạn nhập].
>
> #### Thay thế
>
> `rd` `ngaunhien` `batky` `rdm` `r`
>
> #### Ví dụ
>
> `erand`
>
> `erand 10`
>
> `erand 10 100`

## RDATE

> Đưa ra một ngày bất kỳ trong khoảng thời gian
>
> #### Cú pháp
>
> `erdate [DD/MM/YYYY] [DD/MM/YYYY]`
>
> Nếu bạn không đưa ra thông tin gì, ngày mặc định sẽ lấy sau ngày 01/01/1970.
>
> Nếu bạn nhập một thông tin ngày, ngày sẽ được lấy sau ngày 01/01/1970 và trước ngày bạn nhập.
>
> #### Thay thế
>
> `randomdate` `ngaunhienngay` `datebetween`
>
> #### Ví dụ
>
> `erdate`
>
> `erdate 09/12/2020`
>
> `erdate 09/12/2000 09/12/2020`

## REMOJI

> Đưa ra một emoji bất kỳ trong những server mà bot đã tham gia!
>
> #### Cú pháp
>
> `eremoji`
>
> #### Thay thế
>
> `re` `emoji` `randomemoji`
>
> #### Ví dụ
>
> `eremoji`

## RTIME

> Đưa ra một thời gian ngẫu nhiên trong khoảng thời gian
>
> #### Cú pháp
>
> `rtime [hh:mm] [hh:mm]`
>
> Nếu bạn không đưa ra thông tin gì, thời gian mặc định sẽ lấy sau 0 giờ 0 phút và trước 23 giờ 59 phút.
>
> Nếu bạn nhập một thông tin giờ, thời gian sẽ được lấy sau 0 giờ 0 phút và trước thời gian bạn nhập.
>
> #### Thay thế
>
> `randomtime` `ngaunhiengio` `timebetween`
>
> #### Ví dụ
>
> `ertime`
>
> `ertime 11:11`
>
> `ertime 09:12 12:09`
