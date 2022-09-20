# 第1次作業-作業-HW1
>
>學號：109111106
><br />
>姓名：陳宗鋕
><br />
>作業撰寫時間：30 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2022/09/20
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容
根據題目一開始先將Test.aspx.cs的page_load裡面打上會輸出Hello App的程式


        protected void Page_Load(object sender, EventArgs e)
        {
            Response.Write("Hello App");
        }

 根據題目之後將一個物件button拉到Test.aspx的```<div> <div>```裡面，並按照題目修改其屬性。
```html
<%@ Page Language="C#" AutoEventWireup="true" CodeBehind="Test.aspx.cs" Inherits="_111_1HW1.Text" %>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
            <asp:Button ID="btn_Show" runat="server" Text="Button" OnClick="btn_Click" />
        </div>
    </form>
</body>
</html>
```

根據題目最後將按下按鈕會出現Hello Button的程式打上


         protected void btn_Click(object sender, EventArgs e)
        {
            Response.Write("Hello Button");
        }

至此結束程式內容，最後輸出結果為先顯示Hello App級一個按鈕，按下按鈕會顯示Hello AppHello Button





## 個人認為完成作業須具備觀念

此次作業需先了解如何將按鈕這個物件叫出，其次就是使用各種程式碼來完成顯示Hello App及點選按鈕後出現的Hello Button。。



