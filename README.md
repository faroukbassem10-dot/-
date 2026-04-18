{
  "pharmacy_name": "صيدلية نهاد عبد الرحمن",

  "inventory": [
    {
      "product_id": "P001",
      "name": "بنادول",
      "category": "مسكن",
      "quantity": 25,
      "price": 35,
      "alternative": "باراسيتامول"
    },
    {
      "product_id": "P002",
      "name": "أوجمنتين 1 جم",
      "category": "مضاد حيوي",
      "quantity": 10,
      "price": 120,
      "alternative": "هاي بيوتك"
    },
    {
      "product_id": "P003",
      "name": "كونجستال",
      "category": "برد وانفلونزا",
      "quantity": 4,
      "price": 30,
      "alternative": "فلورست"
    },
    {
      "product_id": "P004",
      "name": "فيتامين سي فوار",
      "category": "فيتامينات",
      "quantity": 18,
      "price": 45,
      "alternative": "سي ريتارد"
    },
    {
      "product_id": "P005",
      "name": "بروفين 400",
      "category": "مسكن",
      "quantity": 0,
      "price": 28,
      "alternative": "كتافلام"
    }
  ],

  "customers": [
    {
      "customer_id": "C001",
      "name": "أحمد محمد",
      "phone": "01012345678",
      "address": "المنصورة - شارع الجمهورية"
    },
    {
      "customer_id": "C002",
      "name": "سارة علي",
      "phone": "01198765432",
      "address": "المنصورة - حي الجامعة"
    }
  ],

  "orders": [
    {
      "order_id": "O001",
      "customer_phone": "01012345678",
      "products": [
        { "name": "بنادول", "quantity": 2 },
        { "name": "فيتامين سي فوار", "quantity": 1 }
      ],
      "total_price": 115,
      "datetime": "2026-04-17 18:30"
    }
  ]
}
