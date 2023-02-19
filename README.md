Hướng dẫn cài đặt và sử dụng phần mềm:
Cài đặt thư viện của openSSL:
  linux: sudo apt-get install libssl-dev

To send mails :
Compile:
 1. Chạy lệnh "make main" để compile ( Yêu cầu cài thư viện make - ubuntu)
 2. Chạy "./main" để chạy chương trình

Nếu kết quả có dạng như sau, chắc chắn đã thành công!

Connected SuccessfullyImage size: 276629
Encoded image length: 368841
Audio size: 4331943
Encoded audio length: 5775925
Video size: 2662488
Encoded audio length: 3549985
0)220 smtp.gmail.com ESMTP z6-20020a637e06000000b00496317241f9sm11072220pgc.51 - gsmtp
250-smtp.gmail.com at your service, [1.55.245.28]
250-SIZE 35882577
250-8BITMIME
250-AUTH LOGIN PLAIN XOAUTH2 PLAIN-CLIENTTOKEN OAUTHBEARER XOAUTH
250-ENHANCEDSTATUSCODES
250-PIPELINING
250-CHUNKING
250 SMTPUTF8
334 VXNlcm5hbWU6
334 UGFzc3dvcmQ6
235 2.7.0 Accepted
250 2.1.5 OK z6-20020a637e06000000b00496317241f9sm11072220pgc.51 - gsmtp
354  Go ahead z6-20020a637e06000000b00496317241f9sm11072220pgc.51 - gsmtp
250 2.0.0 OK  1675329207 z6-20020a637e06000000b00496317241f9sm11072220pgc.51 - gsmtp
221 2.0.0 closing connection z6-20020a637e06000000b00496317241f9sm11072220pgc.51 - gsmtp

To read mails :
1. Tạo app password :
tham khảo tại: https://support.google.com/mail/answer/185833?hl=en
2. Lấy access token cho gmail api :
tham khảo tại: https://blog.vietnamlab.vn/su-dung-google-gmail-api-de-thao-tac-voi-mail/?fbclid=IwAR1MqELjr8958H62X-W_cjCk8giCj_P16ejNI5rMnAgVNeYYbNB1wvs0LdY

