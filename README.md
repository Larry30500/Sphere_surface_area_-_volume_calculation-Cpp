<h1 align="center">
  <br>
  [指定專題作品 C++] 計算球體之表面積與體積
</h1>


## 目錄
* [摘要](#摘要)
* [重點程式碼說明](#重點說明)
* [系統環境](#系統環境)
* [聯絡資訊](#聯絡資訊)
* [致謝](#致謝)
* [權限](#權限)

&nbsp;

## 摘要
### 使用者輸入半徑後，可即時的計算出球體之表面積與體積。


![calculation](images/calculation.gif)

<strong><em>假使想要更加了解此程式的話，請參考本頁面底部之作者的聯絡方式。</em></strong>

&nbsp;

## 重點程式碼說明
### 步驟 1：使用 ```類別 (class)``` 宣告 球體表面積 與 球體體積 的成員函式，並定義其權限為 ```public```。
```cpp
class Class_Sphere
{
  public:
    double sphere_surface_area(double radius)
    {
      ⋮
    }

    double sphere_volume(double radius)
    {
      ⋮
    }
};

```

&nbsp;

### 步驟 2：當使用者輸入半徑後，將計算後的結果輸出。
```cpp
int main()
{
  cout << "請輸入半徑的數值：";
  cin >> current_radius;

  Class_Sphere calculation;

  ⋮

  return 0;
}
```

&nbsp;

## 系統環境
### 本程式所在作業系統
* OS：Windows 7 / 10 (Mac OS、Linux 系統亦可相容)


### 相關套件
* C++ 核心

&nbsp;

## 聯絡資訊
👤 **Larry Jhuang**
  * Email: larry30500@gmail.com

&nbsp;
 
## 致謝
*非常感謝指導老師 (Francesco Ke) 提供程式設計的靈感和方向，並充分教導程式設計的注意事項和相關細節。*

*如果您喜歡此專案，記得點擊⭐️支持作者。*

&nbsp;

## 權限
目前設定為 MIT 權限。請參閱 `LICENSE`，了解更多相關 MIT 權限的規定。

&nbsp;

[[ 返回目錄 ]](#目錄)

