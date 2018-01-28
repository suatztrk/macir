Switch Case yapısı
            Console.WriteLine("Tarafını seç");
            string secim = Console.ReadKey().KeyChar.ToString();
            switch (secim)
            {
                case "A":
                    Console.WriteLine("Seçim a ");
                    break;
                case "B":
                    Console.WriteLine("Seçim B");
                    break;
                case "C":
                    Console.WriteLine("Seçim C");
                    break;

                default:
                    Console.WriteLine("Olmayan bir seçim");
                    //else bloğu
                    break;

            }
            Console.ReadKey();
