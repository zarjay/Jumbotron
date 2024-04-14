# Jumbotron
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <style>
        body {
            background-color: #464646;
            background-image: url(images/background-photo.jpg);
            background-position: center center;
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: cover;
        }

        .jumbotron {
            text-align: center;
            padding: 50px;
            background-color: rgba(255, 255, 255, 0.75);
            margin-bottom: 30px;
        }

        .image-gallery {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .image-gallery figure {
            margin: 0 0 20px;
            width: 100%;
            max-width: 450px;
        }

        .image-gallery img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.2);
        }

        @media (max-width: 767px) {
            .image-gallery figure {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header class="jumbotron">
        <h1>Image Gallery: Tourist Spots in Philippines Photograpy</h1>
    </header>
    <div class="image-gallery">
        <figure>
            <img src="https://www.traveltourxp.com/wp-content/uploads/2017/02/Enchanted-River.jpg?text=Image+1" alt="Image 1">
            <figcaption>"Enchanted River - Do not miss visiting incredible Enchanted River, which you can find in Hinatuan, Surigao del Sur. It is popular tourist attraction in Mindanao that you simply can’t afford to miss. Watch crystal clear azure waters here. Enjoy the thrill of scuba diving in the magical waters of this river.."</figcaption>
        </figure>
        <figure>
            <img src="https://www.traveltourxp.com/wp-content/uploads/2017/02/Dahilayan-Forest-Park.jpg?text=Image+2" alt="Image 2">
            <figcaption>"Dahilayan Forest Park - Dahilayan Forest and Adventure Park that you can find in the landlocked province of Bukidnon is one of the most popular outdoor attractions in Mindanao. It is well-known for various exciting activities that can entertain tourists of all age groups. Dahilayan Forest Park is ideal destination for families and it offers a range of amenities and activities. Dual Zipline in the Adventure Park is regarded as the one of the longest in Asia and you simply can’t miss the zipling experience over here. Do not miss watching various natural scenic views while exploring this park."</figcaption>
        </figure>
        <figure>
            <img src="https://www.traveltourxp.com/wp-content/uploads/2017/02/Tinago-Falls.jpg?text=Image+3" alt="Image 3">
            <figcaption>"Tinago Falls - Plan to visit Tinago Falls during your visit to Mindanao. This awe-inspiring, spectacular waterfall is one of the most visit natural attractions on this island. Its natural beauty of water falling from height is indeed a sight to behold. You can find this stunning fall in the Iligan City. Enjoy going for a dip in the fresh, cold water of this pleasant waterfall."</figcaption>
        </figure>
        <figure>
            <img src="https://www.traveltourxp.com/wp-content/uploads/2017/02/The-Grand-Mosque-Of-Cotabato.jpg?text=Image+4" alt="Image 4">
            <figcaption>"The Grand Mosque Of Cotabato - One of the most popular landmarks of amazing Cotabato City in Mindanao is the Grand Mosque of Cotabato, which is also widely famous as the Sultan Haji Hassanal Bolkiah Masjid. The mosque is indeed an incredible place, and you simply can’t stop admiring the impressive architecture of this mosque."</figcaption>
        </figure>
        <figure>
            <img src="https://www.traveltourxp.com/wp-content/uploads/2017/02/Mount-Apo.jpg?text=Image+5" alt="Image 5">
            <figcaption>"Mount Apo - Make sure you visit magnificent Mount Apo, which is about 2,854 m high. It is a dormant stratovolcano, and it’s well-known as the tallest peak in the nation. Also, Mount Apo is known for being abode to several endemic species that include Waling-waling, Philippine Eage, and other plants and animals. Also, Mt. Apo is home to six aboriginal tribes. As you explore this destination you will find that the peak overlooks amazing Davao City, Kidapawan, and Digos City. You can find many trails from these cities leading to the peak, with the track from Kidapawan is being the easiest.</figcaption>
        </figure>
        <figure>
            <img src="https://gttp.imgix.net/222039/x/0/where-to-go-in-the-philippines-2024-best-tourist-spots-2.jpg?text=Image+6" alt="Image 6">
            <figcaption>"Travel back in time as you stroll along the streets of Calle Crisologo in Vigan as part of your Ilocos itinerary. This 16th-century town, a UNESCO World Heritage Site and a popular tourist spot in the Philippines, quietly boasts old-world charm and Spanish colonial architecture and is the top attraction in Vigan, Ilocos tours and one of the top historical landmarks in the Philippines." </figcaption>
        </figure>
        <figure>
            <img src="https://gttp.imgix.net/222328/x/0/where-to-go-in-the-philippines-2024-best-tourist-spots-4.jpg?text=Image+7" alt="Image 7">
            <figcaption>"Tubbataha Reef is regarded as one of the top diving spots in the Philippines, and, perhaps, the world. Located at the heart of the Sulu Sea, it is considered a center of marine biodiversity and a haven not just for divers but marine conservationists as well. The only way to get to this marine sanctuary is through a liveaboard vessel from Puerto Princesa, Palawan. "</figcaption>
        </figure>
        <figure>
            <img src="https://gttp.imgix.net/222327/x/0/where-to-go-in-the-philippines-2024-best-tourist-spots-3.jpg?auto=compress%2Cformat&ch=Width%2CDPR&dpr=1&ixlib=php-3.3.0&w=883?text=Image+8" alt="Image 8">
            <figcaption>"El Nido in Palawan is most famous for its paradise-like islands and lagoons, but a 45-minute ride from its main town takes you to another idyllic destination: Nacpan Beach. 
                Island hopping escapades in El Nido, including a visit to El Nido Big Lagoon and other top Palawan beaches should not be missed. But after a jam-packed day of visiting coves, white-sand beaches in El Nido, limestone cliffs, and other El Nido Palawan tourist spots, a trip to Nacpan Beach is highly recommended. "</figcaption>
        </figure>
        <figure>
            <img src="https://gttp.imgix.net/222329/x/0/where-to-go-in-the-philippines-2024-best-tourist-spots-5.jpg?text=Image+9" alt="Image 9">
            <figcaption>"As soon as your flight lands at the airport in Bicol International Airport of Albay province, the world’s most perfect volcanic cone and the most active volcano in the Philippines greets you with its majesty. Mayon Volcano is one of the most beautiful places to visit in the Philippines and is a top attraction in any Bicol tour."</figcaption>
        </figure>
        <figure>
            <img src="https://gttp.imgix.net/222141/x/0/where-to-go-in-the-philippines-2024-best-tourist-spots-6.jpg?text=Image+10" alt="Image 10">
            <figcaption>"Take a stroll through history lane within the walled city of Intramuros in Manila, one of the top landmarks in the Philippines. This 64-hectare Spanish fortress was erected by Miguel Lopez de Legazpi and was destroyed by the end of World War II."</figcaption>
        </figure>
        <figure>
            <img src="https://gttp.imgix.net/222347/x/0/where-to-go-in-the-philippines-2024-best-tourist-spots-7.jpg?text=Images+11" alt="Image 11">
            <figcaption>"Locals and foreign visitors from Manila often take a quick escape from the megacity and make their way south to Tagaytay, a relaxing town famous for its cool weather, magnificent views, and many tourist spots. It's popular for being one of the best kid-friendly places near Manila.</figcaption>
        </figure>
        <figure>
            <img src="https://gttp.imgix.net/222334/x/0/where-to-go-in-the-philippines-2024-best-tourist-spots-14.jpg?text=Images+12" alt="Image 12">
            <figcaption>Siargao’s rise as a top tourist destination in the Philippines is nothing short of meteoric. Once a sleepy island in Surigao del Norte, it has become one of the favorite destinations and playgrounds for travelers, and it is primarily because of one activity: surfing.
                     It is now known as the Philippines' surfing capital, and some even regard it as the surfing mecca of Asia.</figcaption>
        </figure>
    </div>
</body>
</html>
