<h2>工具:</h2><br>
python folium 可視化套件<br>
  1.Choropleth <br>
  2.HeatMap<br>
    2.1Marker標記10大車禍地點(桃園)<br>
    3.Circle 車禍分布熱圖<br>
geojson 取得縣市各區域(鄉鎮市區行政區域界線 sheet hub)<br>
  1.使用欄位 T_UID  OBJECTID<br>
mapbox studio 更改地圖背景格式api <br>

<h2>流程:</h2><br>
1.透過sheet hub抓取各縣市地圖邊界   (第一層)<br>
2.取得mapbox選取地圖背景格式 api   (背景)<br>
3.取得各資料之經緯度<br>
4.透過folium 進行視覺化<br>


<h2>folium 套件可視化</h2><br>
桃園:<br>
    Choropleth:<br>
      count各個縣市的車禍次數，並標記於地圖上。<br>
    HeatMap:<br>
      count各個縣市的車禍次數，並標記於地圖上，並透過Marker標籤標記10大車禍地點。<br>
    Circle(泡泡圖):<br>
      計算每個車禍地點(經緯度)位置，重複出現之次數，而圓圈大小與顏色依照車禍地點發生次數訂定。<br>
      
        2-10
        
        10-20
        
        20-40
      
      40-60
      
      60
  
  
<h2>台中:</h2>


Choropleth:

依照3群後不同的條件進行設定(表5表6)，並標記於地圖上。





