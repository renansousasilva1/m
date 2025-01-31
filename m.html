{% load static %}
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pista Maps</title>


    <script src="https://cdn.jsdelivr.net/gh/placemark/leaflet-kml@main/leaflet-kml.js"></script>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <link rel="stylesheet" href="https://js.api.here.com/v3/3.1/mapsjs-ui.css" />
    <script src="https://js.api.here.com/v3/3.1/mapsjs-core.js"
            type="text/javascript" defer></script>
    <script src="https://js.api.here.com/v3/3.1/mapsjs-service.js"
            type="text/javascript" defer></script>
    <script src="https://js.api.here.com/v3/3.1/mapsjs-ui.js"
            type="text/javascript" defer></script>
    <script src="https://js.api.here.com/v3/3.1/mapsjs-mapevents.js"
            type="text/javascript" defer></script>
    <script src="https://js.api.here.com/v3/3.1/mapsjs/controls/AbstractControl.js"
            type="text/javascript" defer></script>
    <script src="https://js.api.here.com/v3/3.1/mapsjs/controls/Control.js"
            type="text/javascript" defer></script>
    <script src="https://js.api.here.com/v3/3.1/mapsjs/controls/MapEvents.js"
            type="text/javascript" defer></script>
    <script src="https://js.api.here.com/v3/3.1/mapsjs/ui/Ui.js"
            type="text/javascript" defer></script>
    <script src="https://js.api.here.com/v3/3.1/mapsjs/ui/MapUi.js"
            type="text/javascript" defer></script>
    
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200&icon_names=my_location" />

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0&icon_names=search" />
    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" />
    <script src="https://unpkg.com/leaflet-omnivore@1.1.0/leaflet-omnivore.min.js"></script>
    <!-- Leaflet JS -->
  <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>
  <!-- Biblioteca para lidar com KMZ e KML -->
  <script src="https://cdn.jsdelivr.net/npm/jszip/dist/jszip.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/togeojson/0.16.0/togeojson.min.js"></script>

  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/shorthandcss@1.1.1/dist/shorthand.min.css" />
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Muli:200,300,400,500,600,700,800,900&display=swap" />
  <link rel="stylesheet" type="text/css" href="https://bit.ly/CODFONT-ISCA" />
  
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css" />
  <link rel="stylesheet" href="{% static 'css/style.css' %}">
  <link rel="stylesheet" href= "{% static 'css/style-mapa.css' %}">
  <link rel="stylesheet" href= "{% static 'css/style-index.css' %}">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200&icon_names=my_location" />

  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0,0&icon_names=search" />

  <script src="https://unpkg.com/feather-icons"></script>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>


</head>

{% block content %}


<body style="background-color:white;">
    <nav class="navbar">
        <div class="container">
            <a href="{%url 'home'%}" class="brand"> <img src="/static/logo.png" style="width:40px; height:auto;"></a>
            <button class="toggle-menu" id="toggle-menu">
                ☰
            </button>
            {% if user.is_authenticated %}
                <ul class="nav-links" id="nav-links" style="margin-block: auto;">
                    <li><a href="{% url 'home' %}">Home</a></li>
                    <li><a href="{% url 'mapa' %}">Mapa</a></li>
                    <li><a href="{% url 'legenda' %}">Legenda</a></li>
                    <li><a href="{% url 'contato' %}">Contato</a></li>
                    <li><a href="{% url 'premium' %}">Planos Premium</a></li>
                    <li><a href="{% url 'minhaconta' %}">Minha Conta</a></li>
                    <li><a href="{% url 'logout' %}">Logout</a></li>
                </ul>
            {% else %}
                <ul class="nav-links" id="nav-links" style="margin-block: auto;">
                    <li><a href="{% url 'home' %}">Home</a></li>
                    <li><a href="{% url 'mapa' %}">Mapa</a></li>
                    <li><a href="{% url 'legenda' %}">Legenda</a></li>
                    <li><a href="{% url 'contato' %}">Contato</a></li>
                    <li><a href="{% url 'premium' %}">Planos Premium</a></li>
                    <li><a href="{% url 'login' %}">Login</a></li>
                </ul>
            {% endif %}

            
        </div>
    </nav>
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script>
        $(document).ready(function () {
            $('#toggle-menu').click(function () {
                $('#nav-links').toggleClass('active');
            });
        });
    </script>

<style>
        .locate-button {
            position: absolute;
            display: flex
        ;
            align-items: center;
            margin-top: -143px;
            right: 10px;
            z-index: 2;
            background-color: white;
            border: 1px solid #ccc;
            border-radius: 10px;
            height: 33px;
            width: 35px;
            padding: 8px;
            padding-left: 5px;
            padding-top: 8.5px;
            cursor: pointer;
        }

        .navbar{
            z-index:40;
        }

       
        #map{
            margin-top:-35px;
            margin-left:-8px;
            height:96.5vh;
            width:100.7%;
        }
        
        /* Estilos para a box lateral */
        .route-bar{
            width:355px;
        }
        .search-bar {
            display: flex;
            align-items: center;
            background-color: white;
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 5px 10px;
            width: 355px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .route-box {
            background: white;
            padding: 10px;
            padding-left: 18px;
            margin-left: -100px;
            border-radius: 5px;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.2);
            max-width: 390px;
            width: 950px;
            height: 1675px;
            font-family: Arial, sans-serif;}


        .route-item {
            margin-bottom: 10px;
        }
        .route-item p {
            margin: 0;
        }
        #input-container {
            margin-bottom: 10px;
            padding: 10px;
            background: white;
            box-shadow: 0 2px 6px rgba(0, 0, 0, 0.2);
            border-radius: 5px;
            max-width: 300px;
        }
        #input-container input {
            margin: 5px 0;
            padding: 5px;
            width: 100%;
            box-sizing: border-box;
        }
    
            .hidden {
                display: none;
            }
            
            #sidebar {
                background-color: white;
                padding: 10px;
                border-radius: 5px;
                width: 300px;
                position: absolute;
                top: 10px;
                left: 10px;
                z-index: 1000;
            }
            
            #map {
                width: 100.8%;
                height: 97.4vh;
                margin-left:0px !important;
                margin-top: 0px !important;
            }
            
        
</style>

    <script src="https://unpkg.com/leaflet-omnivore@latest/leaflet-omnivore.min.js">
    </script>

</header>

<style>
#map{
    margin-top:0px !important;
}

</style>
    
<body>


    <title>Mapa das Favelas 🗺️ - PistaMaps | 2022</title>
</head>


<body>
    
    <!-- Formulário de Entrada -->
    <div class="container-fluid"style="z-index: 2;position: absolute;background-color: white;height: 140px;width: 313px;margin-left: 20px;margin-top: 23px;border-radius: 10px;padding-left: 10px;">

        <form class="form-horizontal">
            <div class="form-group">
                <label for="origin" style="width: 265px;">Indo de:</label>
                <input type="text" id="origin" placeholder="Indo de:" class="form-control">
            </div>

            <div class="form-group">
                <label for="destination" style="width: 265px;">Para:</label>
                <input type="text" id="destination" placeholder="Para:" class="form-control">
            </div>
        </form>
        
        <div class="text-center mt-3">
            <button class="btn btn-success btn-lg" onclick="calculateDistance();" style="margin-left: -190px;margin-top: 8px;font-size: 13px;">TRAÇAR ROTAS</button>
        </div>
    </div>

    <div id="map" style="width:100%; height:500px;"></div>
    <div id="output" ></div>

    <script>
        function initMap() {
            // Opções do mapa
            var myLatLng = { lat: -22.906235, lng: -43.170280 };
            var mapOptions = {
                center: myLatLng,
                zoom: 10,
                mapTypeId: google.maps.MapTypeId.HYBRID,
                mapTypeControl: true,
                zoomControl: true,
                scaleControl: true,
                streetViewControl: false,
            };

            // Criar o mapa
            var map = new google.maps.Map(document.getElementById("map"), mapOptions);

            // Ícone do GPS
            var iconeGPS = {
                url: 'https://lh3.googleusercontent.com/ogw/AOh-ky3UfCBQBHHTzrRzk5OHh0Y5q8Pz8BUbuMapWCgU=s32-c-mo'
            };

            // Adicionar camada de tráfego
            var trafficLayer = new google.maps.TrafficLayer();
            trafficLayer.setMap(map);

            // Criar marcador de posição
            var marker = new google.maps.Marker({
                map: map,
                draggable: false,
                icon: iconeGPS,
                title: 'Minha Localização - Eu estou próximo daqui!',
            });

            // Monitorar localização do usuário
            if (navigator.geolocation) {
                navigator.geolocation.watchPosition(
                    function (position) {
                        marker.setPosition({
                            lat: position.coords.latitude,
                            lng: position.coords.longitude,
                        });
                    },
                    function (error) {
                        console.error("Erro na geolocalização: ", error);
                    },
                    { enableHighAccuracy: true }
                );
            } else {
                console.error("Geolocalização não é suportada pelo seu navegador.");
            }

            // Camada KML
            new google.maps.KmlLayer({
                url: "https://www.google.com/maps/d/kml?mid=1PmDUHTSeFGN2-NGAQyzbTA92cPS5weN1&usp=sharing",
                map: map,
            });

            // Criar serviço de rotas
            var directionsService = new google.maps.DirectionsService();
            var directionsDisplay = new google.maps.DirectionsRenderer({
                draggable: true,
                map: map,
                polylineOptions: {
                    strokeColor: "white",
                    strokeOpacity: 1.0,
                    strokeWeight: 7,
                }
            });
            directionsDisplay.setMap(map);

            // Função para calcular rota
            window.calculateDistance = function () {
                var request = {
                    origin: document.getElementById("origin").value,
                    destination: document.getElementById("destination").value,
                    travelMode: google.maps.TravelMode.DRIVING,
                    unitSystem: google.maps.UnitSystem.METRIC,
                };

                directionsService.route(request, function (result, status) {
                    var output = document.getElementById("output");
                    if (status === google.maps.DirectionsStatus.OK) {
                        output.innerHTML = `
                            <p class='alert-success'> 
                                <b>Saindo de:</b> ${document.getElementById("origin").value} <br>
                                <b>Indo para:</b> ${document.getElementById("destination").value} <br>
                                <b>Distância:</b> ${result.routes[0].legs[0].distance.text} <br>
                                <b>Duração:</b> ${result.routes[0].legs[0].duration.text} 
                            </p>`;
                        directionsDisplay.setDirections(result);
                    } else {
                        output.innerHTML = "<div class='alert-danger'>Não foi possível calcular a rota.</div>";
                    }
                });
            };
        }
    </script>

    <script async defer src="https://maps.googleapis.com/maps/api/js?key=AIzaSyClZ8Fn3e432e2UZBKSqXCuRHF0AxTgs1I&callback=initMap&libraries=places"></script>
</body>
</html>
