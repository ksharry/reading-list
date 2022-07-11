<table>
    <tr>
        <td>現代JavaScript教程</td>
    </tr>
</table>

## 僅個人筆記
## [網路課程](https://zh.javascript.info/)

## 第一部分：JavaScript 編程語言
#### 簡介
1. JavaScript 簡介
2. 手冊與規範
3. 代碼編輯器
4. 開發者控制台
#### JavaScript 基礎知識
1. Hello, world!
2. 代碼結構
3. 現代模式，"use strict"
4. 變量
5. 數據類型
6. 交互：alert、prompt 和confirm
7. 類型轉換
8. 基礎運算符，數學
9. 值的比較
10. 條件分支：if 和'?'
11. 邏輯運算符
12. 空值合併運算符'??'
13. 循環：while 和for
14. switch 語句
15. 函數
16. 函數表達式
17. 箭頭函數，基礎知識
18. JavaScript 特性
#### 代碼質量
1. 在瀏覽器中調試
2. 代碼風格
3. 註釋
4. 忍者代碼
5. 使用Mocha 進行自動化測試
6. Polyfill 和轉譯器
#### Object（對象）：基礎知識
1. 對象
2. 對象引用和復制
3. 垃圾回收
4. 對象方法，"this"
5. 構造器和操作符"new"
6. 可選鏈"?."
7. symbol 類型
8. 對象— 原始值轉換

#### 數據類型
1. 原始類型的方法
2. 數字類型
3. 字符串
4. 數組
5. 數組方法
6. Iterable object（可迭代對象）
7. Map and Set（映射和集合）
8. WeakMap and WeakSet（弱映射和弱集合）
9. Object.keys，values，entries
10. 解構賦值
11. 日期和時間
12. JSON 方法，toJSON

#### 函數進階內容
1. 遞歸和堆棧
2. Rest 參數與Spread 語法
3. 變量作用域，閉包
4. 老舊的"var"
5. 全局對象
6. 函數對象，NFE
7. new Function 語法
8. 調度：setTimeout 和setInterval
9. 裝飾器模式和轉發，call/apply
10. 函數綁定
11. 深入理解箭頭函數

#### 對象屬性配置
1. 屬性標誌和屬性描述符
2. 屬性的getter 和setter

#### 原型，繼承
1. 原型繼承
2. F.prototype
3. 原生的原型
4. 原型方法，沒有__proto__ 的對象

#### 類
1. Class 基本語法
2. 類繼承
3. 靜態屬性和靜態方法
4. 私有的和受保護的屬性和方法
5. 擴展內建類
6. 類檢查："instanceof"
7. Mixin 模式

#### 錯誤處理
1. 錯誤處理，"try...catch"
2. 自定義Error，擴展Error
#### Promise，async/await
1. 簡介：回調
2. Promise
3. Promise 鏈
4. 使用promise 進行錯誤處理
5. Promise API
6. Promisification
7. 微任務（Microtask）
8. Async/await

#### Generator，高級iteration
1. Generator
2. 異步迭代和generator
#### 模塊
1. 模塊(Module) 簡介
2. 導出和導入
3. 動態導入
#### 雜項
1. Proxy 和Reflect
2. Eval：執行代碼字符串
3. 柯里化（Currying）
4. Reference Type
5. BigInt

## 第二部分：瀏覽器：文檔，事件，接口
#### Document
1. 瀏覽器環境，規格
2. DOM 樹
3. 遍歷DOM
4. 搜索：getElement*，querySelector*
5. 節點屬性：type，tag 和content
6. 特性和屬性（Attributes and properties）
7. 修改文檔（document）
8. 樣式和類
9. 元素大小和滾動
10. Window 大小和滾動
11. 坐標

#### 事件簡介
1. 瀏覽器事件簡介
2. 冒泡和捕獲
3. 事件委託
4. 瀏覽器默認行為
5. 創建自定義事件

#### UI 事件
1. 鼠標事件
2. 移動鼠標：mouseover/out，mouseenter/leave
3. 鼠標拖放事件
4. 指針事件
5. 鍵盤：keydown 和keyup
6. 滾動

#### 表單，控件
1. 表單屬性和方法
2. 聚焦：focus/blur
3. 事件：change，input，cut，copy，paste
4. 表單：事件和方法提交

#### 加載文檔和其他資源
1. 頁面生命週期：DOMContentLoaded，load，beforeunload，unload
2. 腳本：async，defer
3. 資源加載：onload，onerror

#### 雜項
1. DOM 變動觀察器（Mutation observer）
2. 選擇（Selection）和範圍（Range）
3. 事件循環：微任務和宏任務


## 第三部分：其他文章
#### Frame 和window
1. 彈窗和window 的方法
2. 跨窗口通信
3. 點擊劫持攻擊

#### 二進制數據，文件
1. ArrayBuffer，二進制數組
2. TextDecoder 和TextEncoder
3. Blob
4. File 和FileReader

#### 網絡請求
1. Fetch
2. FormData
3. Fetch：下載進度
4. Fetch：中止（Abort）
5. Fetch：跨源請求
6. Fetch API
7. URL 對象
8. XMLHttpRequest
9. 可恢復的文件上傳
10. 長輪詢（Long polling）
11. WebSocket
12. Server Sent Events

#### 在瀏覽器中存儲數據
1. Cookie，document.cookie
2. LocalStorage，sessionStorage
3. IndexedDB

#### 動畫
1. 貝塞爾曲線
2. CSS 動畫
3. JavaScript 動畫
4. Web components
5. 從星球軌道的高度講起
6. Custom elements
7. 影子DOM（Shadow DOM）
8. 模板元素
9. Shadow DOM 插槽，組成
10. 給Shadow DOM 添加樣式
11. Shadow DOM 和事件（events）

#### 正則表達式
1. 模式（Patterns）和修飾符（flags）
2. 字符類
3. Unicode：修飾符“u” 和class \p{...}
4. 錨點（Anchors)：字符串開始^ 和末尾 $
5. Flag "m" — 多行模式
6. 詞邊界：\b
7. 轉義，特殊字符
8. 集合和範圍[...]
9. 量詞`+,*,?` 和`{n}`
10. 貪婪量詞和惰性量詞
11. 捕獲組
12. 模式中的反向引用：\N 和\k<name>
13. 選擇（OR）|
14. 前瞻斷言與後瞻斷言
15. 災難性回溯
16. 粘性標誌"y"，在位置處搜索
17. 正則表達式（RegExp）和字符串（String）的方法
