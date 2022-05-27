package com.company;



public class Main {

    public static void main(String[] args) {
        Rose rose = new Rose("red",56);
        Tulip tulip = new Tulip("red",45);
        Chamomile chamomile = new Chamomile("white",35);
        Narcissus narcissus = new Narcissus("whit",30);


        Flowers[] flowers = new Flowers[]{rose,tulip,chamomile,narcissus};
        int price = 0;
        for(int i = 0; i < flowers.length; i++){
            price = flowers[i].getPrice() + price;
        }
        System.out.println("Ціна букету = " + price);

    }
}
