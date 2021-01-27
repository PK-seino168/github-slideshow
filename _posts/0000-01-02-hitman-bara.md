layout: slide
title: "２枚目のスライドにようこそ！"
---
何かを書く。
戻るには戻るボタンを使いましょう！

//金銭のjava beansが完成しました
public class tax{
  
    public tax(){}
    public tax(int tax){
        this.tax = tax;
    }
    //金銭の設定
    private void setTax(int tax){
        this.tax = tax;
    }
    //金銭の取得
    private int getTax(){
        return tax;
    }
}
