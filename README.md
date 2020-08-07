# du-attend-tool
대구대 전자출결 툴

코로나 시대에 앉아서 전자출결 합시다!!

필요한 것
1. 학번
2. 강의실 벽면에 부착된 QR코드(처음 등록 후 브라우저에 저장)
3. 32자리 QR코드 키

복호화( http://icyberchef.com/ )
 - AES
 - ECB
 - Input: Hex
 - Output: Raw
 
 참고사항
 - QR코드 스캔은 https에서만 됨. ( https://stackoverflow.com/questions/16835421/how-to-allow-chrome-to-access-my-camera-on-localhost )
 - 카카오톡 브라우저나 퍼핀 등 외부 브라우저에서 스캐너 동작 안 되는 경우 있음.
 - 대구대 아이피 대역이 아니면 출석 불가 
