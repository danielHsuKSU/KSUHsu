A.1. 電腦通訊概說
   A.1.1.電腦與網路:基本觀念
   A.1.2.資訊傳輸模式
   A.1.3.網路傳輸速度
   A.1.4.電腦網路的類型
A.2. 網路的組成與架構
   A.2.1. 電腦網路的功能
   A.2.2. 區域網路的拓樸
          拓撲(Topology)==網路連接的型態

   A.2.3. 電腦網路分享架構:Client/server與P2P



A.3.1.通訊協定與標準

A.3.2. OSI通訊標準
A.3.3. TCP/IP協定
A.3.4. [IEEE 802](https://en.wikipedia.org/wiki/IEEE_802)
   
A.3.4. 傳輸層重要協定:TCP vs UDP
        A.3.4.1 TCP vs UDP
        A.3.4.2 TCP的三向交握

A.3.5. IP與DNS(網域名稱)
        A.3.5.1. IP協定與IP位址
        A.3.5.2. DNS
=============================================
# [OSI七層](https://zh.wikipedia.org/wiki/OSI%E6%A8%A1%E5%9E%8B) : https://zh.wikipedia.org/wiki/OSI%E6%A8%A1%E5%9E%8B

### 1 實體層

#### 實體層（Physical Layer）在局部區域網路上傳送資料框（Data Frame），它負責管理電腦通訊裝置和網路媒體之間的互通。包括了針腳、電壓、線纜規範、集線器、中繼器、網卡、主機介面卡等。

### 2 資料連結

#### 資料連結層（Data Link Layer）負責網路尋址、錯誤偵測和改錯。當表頭和表尾被加至數據包時，會形成資訊框（Data Frame）。數據連結串列頭（DLH）是包含了實體位址和錯誤偵測及改錯的方法。數據連結串列尾（DLT）是一串指示數據包末端的字串。例如乙太網、無線區域網路（Wi-Fi）和通用分組無線服務（GPRS）等。分為兩個子層：邏輯鏈路控制（logical link control，LLC）子層和媒介存取控制（Media access control，MAC）子層。

### 3 網路層

#### 網路層（Network Layer）決定數據的路徑選擇和轉寄，將網路表頭（NH）加至數據包，以形成封包。網路表頭包含了網路資料。例如:網際網路協定（IP）等。

### 4 傳輸層

#### 傳輸層（Transport Layer）把傳輸表頭（TH）加至數據以形成數據包。傳輸表頭包含了所使用的協定等傳送資訊。例如:傳輸控制協定（TCP）等。

### 5 會議層

#### 會議層（Session Layer）負責在數據傳輸中設定和維護電腦網路中兩台電腦之間的通訊連接。

### 6 表達層

#### 表達層（Presentation Layer）把數據轉換為能與接收者的系統格式相容並適合傳輸的格式。

### 7 應用層

#### 應用層（Application Layer）提供為應用軟體而設計的介面，以設定與另一應用軟體之間的通訊。例如：HTTP、HTTPS、FTP、Telnet、SSH、SMTP、POP3等。

--------
# [七層舉例](https://www.ithome.com.tw/tech/47085) : https://www.ithome.com.tw/tech/47085

### 1 實體層

#### 網線 網卡 等設備

### 2 資料連結

#### 這組訊號稱為資料訊框（Data Frame）。訊框內包含媒體存取控制（Media Access Control，MAC）位址

### 3 網路層

### 4 傳輸層

### 5 會議層

### 6 表達層

### 7 應用層


