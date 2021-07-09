<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web GIS Kabupaten Pangandaran</title>
    <!-- Plugin CSS dan Script -->
    <link rel="stylesheet" href="src/leaflet.css">
    <link rel="stylesheet" href="src/css/bootstrap.css">
    <link rel="stylesheet" href="src/plugins/L.Control.MousePosition.css">
    <link rel="stylesheet" href="src/plugins/L.Control.Sidebar.css">
    <link rel="stylesheet" href="src/plugins/Leaflet.PolylineMeasure.css">
    <link rel="stylesheet" href="src/plugins/easy-button.css">
    <link rel="stylesheet" href="src/plugins/leaflet-styleeditor/css/Leaflet.StyleEditor.css">
    <link rel="stylesheet" href="src/css/font-awesome.min.css">
    <link rel="stylesheet" href="src/plugins/leaflet.awesome-markers.css">
    <link rel="stylesheet" href="src/plugins/leaflet-mapkey/MapkeyIcons.css">
    <link rel="stylesheet" href="src/plugins/leaflet-mapkey/L.Icon.Mapkey.css">
    <link rel="stylesheet" href="src/plugins/MarkerCluster.css">
    <link rel="stylesheet" href="src/plugins/MarkerCluster.Default.css">
    <link rel="stylesheet" href="src/plugins/leaflet-legend.css">
    <link rel="stylesheet" href="src/jquery-ui.min.css">

    <script src="src/leaflet-src.js"></script>
    <script src="src/jquery-3.2.0.min.js"></script>
    <script src="src/plugins/L.Control.MousePosition.js"></script>
    <script src="src/plugins/L.Control.Sidebar.js"></script>
    <script src="src/plugins/Leaflet.PolylineMeasure.js"></script>
    <script src="src/plugins/easy-button.js"></script>
    <script src="src/plugins/leaflet-providers.js"></script>
    <script src="src/plugins/leaflet-styleeditor/javascript/Leaflet.StyleEditor.js"></script>
    <script src="src/plugins/leaflet-styleeditor/javascript/Leaflet.StyleForms.js"></script>
    <script src="src/plugins/leaflet.ajax.min.js"></script>
    <script src="src/plugins/leaflet.sprite.js"></script>
    <script src="src/plugins/leaflet.awesome-markers.min.js"></script>
    <script src="src/plugins/leaflet-mapkey/L.Icon.Mapkey.js"></script>
    <script src="src/plugins/leaflet.markercluster.js"></script>
    <script src="src/plugins/leaflet.geometryutil.js"></script>
    <script src="src/plugins/leaflet-legend.js"></script>
    <script src="src/jquery-ui.min.js"></script>
    <script src="src/turf.min.js"></script>

    <!-- Menu Bar Sebelah Kiri -->
    <style>
        #mapdiv {
            height: 100vh;
        }

        #divSekolah {
            background-color: beige;
        }

        #divJalan {
            background-color: darkorange;
        }

        .errorMsg {
            padding: 0;
            text-align: center;
            background-color: darksalmon;
        }

        .col-xs-12,
        .col-xs-6,
        .col-xs-4 {
            padding: 3px;
        }
    </style>
</head>

<body>
    <!-- Sidebar -->
    <div id="side-bar" class="col-md-3">
        <!-- Button locate-->
        <button id='btnlocate' class='btn btn-primary btn-block'><b>Web Map Kabupaten Pangandaran</b>
        </button>
        <br>

        <div id="divFilterRumah" Class="col-xs-12">
            <div Class="col-xs-3">

                <tabel id="headLogos">
                    <tbody>
                        <tr>
                            <td align="right">
                                <img id="logowilayah" src="src/images/wilayah.png" style="height: 50px;">
                            </td>
                        </tr>
                    </tbody>
                </tabel>
            </div>
            <div class="col-xs-2">
                <br>
                <p><i>dan</i></p>
            </div>
            <div class="col-xs-3">
                <table id="headlogos">
                    <tbody>
                        <tr>
                            <td aligen="left">
                                <img id="upblogo" src="src/images/upb.png" style="height: 30px;">
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
        <button id="btnShowLegend" class='btn-primary btn-block'>
            <b>LEGENDA</b>
        </button>

        <div id="legend">
            <div id="lgndRumah">

                <h4 class="text-center">Sekolah<i id="btnSekolah" class="fa fa-server"></i></h4>
                <div id="lgndSekolahDetail">
                    <svg height="90" widht="100%">
                        <circle cx="25" cy="15" r="10" style=" stroke-width: 4;stroke: deeppink; fill: chartreuse; fill-opacity:0.5;" />
                        <text x="50" y="20" style="font-family: sans-serif; font-size:16px;">SMK</text>
                        <circle cx="25" cy="45" r="10" style="stroke-width: 4px; stroke: green; fill: chartreuse; fill-opacity:0.5;" />
                        <text x="50" y="50" style="font-family: sans-serif; font-size:16px;">SMA</text>
                        <circle cx="25" cy="75" r="10" style="stroke-width: 4px; stroke: Blue; fill: chartreuse; fill-opacity:0.5;" />
                        <text x="50" y="80" style="font-family: sans-serif; font-size:16px;">MA</text>
                    </svg>
                </div>
                <div id="lgndAdministrasi">
                    <h4 class="text-center">Batas Administrasi<i id="btnAdministrasi" class="fa fa-server"></i></h4>
                    <div id="lgndAdministrasiDetail">
                        <svg height="120" widht="100%">
                            <line x1="10" y1="10" x2="60" y2="10" style="stroke: #C71585; stroke-width: 5; stroke-dasharray: 7,5,3,5;" />
                            <text x="65" y="15" style="font-family: sans-serif; font-size:16px;">Batas Propinsi</text>
                            <line x1="10" y1="40" x2="60" y2="40" style="stroke: #2bdf94; stroke-width: 3; stroke-dasharray: 7,5,3,5,3,5;" />
                            <text x="65" y="45" style="font-family: sans-serif; font-size: 16px;">Batas Kabupaten</text>
                            <line x1="10" y1="70" x2="60" y2="70" style="stroke: #351c75; stroke-width: 2,5; stroke-dasharray: 7,5,3,5,3,5,3,5;" />
                            <text x="65" y="75" style="font-family: sans-serif; font-size: 16px;">Batas Kecamatan</text>
                            <line x1="10" y1="100" x2="60" y2="100" style="stroke: #f1c232; stroke-width: 1,5; stroke-dasharray: 7,5,3,5,3,5,3,5,3,5;" />
                            <text x="65" y="105" style="font-family: sans-serif; font-size: 16px;">Batas Desa</text>
                        </svg>
                    </div>
                </div>

                <div id="lgndLanduse">
                    <h4 class="text-center">Lahan Pertanian<i id="btnLanduse" class="fa fa-server"></i></h4>
                    <div id="lgndLanduseDetail">
                        <svg height="100" widht="100%">
                            <rect x="10" y="5" width="30" height="20" style="fill:#FFA500; fill-opacity:0.5;" />
                            <text x="50" y="20" style="font-family: sans-serif; font-size:16px;">Sawah</text>
                            <rect x="10" y="35" width="30" height="20" style="fill:#00FFFF; fill-opacity:0.5;" />
                            <text x="50" y="50" style="font-family: sans-serif; font-size:16px;">Kebun</text>
                            <rect x="10" y="65" width="30" height="20" style="fill:#A52A2A; fill-opacity:0.5;" />
                            <text x="50" y="80" style="font-family: sans-serif; font-size:16px;">Ladang</text>
                        </svg>
                    </div>
                </div>

                <div id="lgndJalan">
                    <h4 class="text-center">Jaringan Jalan<i id="btnJalan" class="fa fa-server"></i></h4>
                    <div id="lgndJalanDetail">
                        <svg height="130" widht="100%">
                            <line x1="10" y1="10" x2="60" y2="10" style="stroke:Red; stroke-width:6;" />
                            <text x="65" y="15" style="font-family: sans-serif; font-size:16px;">Jalan Kolektor</text>
                            <line x1="10" y1="40" x2="60" y2="40" style="stroke:Orange; stroke-width:4;" />
                            <text x="65" y="45" style="font-family: sans-serif; font-size:16px;">Jalan Setapak</text>
                            <line x1="10" y1="70" x2="60" y2="70" style="stroke:Blue; stroke-width:2;" />
                            <text x="65" y="75" style="font-family: sans-serif; font-size:16px;">Jalan Lokal</text>
                            <line x1="10" y1="100" x2="60" y2="100" style="stroke: deeppink; stroke-width:4;" />
                            <text x="65" y="105" style="font-family: sans-serif; font-size:16px;">Jalan Lain</text>
                        </svg>
                    </div>
                </div>

            </div>

            <!--Menu Searching Rumah-->
            <div id="divSekolah" class="col-xs-12">
                <div id="divSekolahLabel" class="text-center col-xs-12">
                    <h4>Pencarian Sekolah</h4>
                </div>
                <div id="divSekolahError" class="errorMsg col-xs-12"></div>
                <div id="divFindSekolah" class="form-group">
                    <div class="col-xs-6">
                        <input type="text" id="txtFindSekolah" class="form-control" placeholder="Masukan Nama Sekolah">
                    </div>
                    <div class="col-xs-6">
                        <button id="btnFindSekolah" class="btn btn-primary btn-block">Cari</button>
                    </div>
                    <div id="divFilterSekolah" class="col-xs-112"></div>
                    <div class="col-xs-3">
                        <input type="radio" name="filterSekolah" value="ALL" checked>All
                    </div>
                    <div class=" col-xs-3">
                        <input type="radio" name="filterSekolah" Value="SMK">SMK
                    </div>
                    <div class=" col-xs-3">
                        <input type="radio" name="filterSekolah" Value="SMA">SMA
                    </div>
                    <div class=" col-xs-3">
                        <input type="radio" name="filterSekolah" Value="MA">MA
                    </div>

                </div>
                <div class="" id="divSekolahData">
                </div>
            </div>

            <!--//Menu Jalan-->

            <div id="divfilterJalan" class="col-xs-12">
                <div id="divJalanLabel" class="text-center col-xs-12">

                </div>
                <div class="" id="divJalanData"></div>
            </div>

            <!--TENTANG-->

            <!--Button Locate-->
            <button id='btnTentang' class='btn btn-primary btn-block'><b>TENTANG</b></button><br>

            <div class="panel p-0 m-0 au-target" id.bind="'vid_'+ menuName" ref.bind="'vid_'+ menuName" au-target-id="103" id="vid_about" style="display:block;">

                <!--INFO-->
                <div id="content-info" class="contentWrapper text-center">

                    <p id="intro">Web GIS Daerah Pangandara ini dibuat untuk memenuhi UJIAN AKHIR SEMESTER <br>UNIVERSITAS PERADABAN BUMIAYU BREBES <br> Prodi: Teknik Informatika semester 4 <br>Mata Kuliah: SISTEM INFORMASI GEOGRAFIS  <br> oleh : Khusniyati 42419012 <br>Web GIS ini dibuat menggunakan leaflet js, bootstrap, jQuery dan ajax. </p>

                </div>
            </div>
            <!--anchor-->
        </div>

    </div>
    <!--Halaman Utama-->
    <div id="mapdiv" class="col-md-12"></div>

    <script>
        // Variabel yang akan digunakan
        var mymap;

        var lyrOSM;
        var lyrWatercolor;
        var lyrTOPO;
        var lyrImagery;
        var lyrOutdoors;


        var lyrJalan;
        var lyrSekolah;
        var lyrAdministrasi;

        var lyrLanduse;
        var lyrSearch;
        var lyrMarkerCluster;

        var ctlLayers;

        var ctlEasybutton;
        var ctlSidebar;
        var ctlPan;
        var ctlMouseposition;
        var ctlMmeasure;
        var ctlAttribute;
        var ctlStyle;
        var ctlLegend;

        var mrkCurentLocation;

        var objBasemaps;
        var objOverlays;
        var arSekolahIDs = [];
        var arAdministrasiIDs = [];

        var arLanduseIDs = [];

        var arJalanIDs = [];

        // Function
        $(document).ready(function() {
            /*Maps Intiliazation*/
            mymap = L.map('mapdiv', {
                center: [-7.696, 108.655],
                zoom: 14,
                attributionControl: false
            });

            ctlSidebar = L.control.sidebar('side-bar').addTo(mymap);

            ctlEasybutton = L.easyButton('glyphicon-transfer', function() {
                ctlSidebar.toggle();
            }).addTo(mymap);

            ctlAttribute = L.control.attribution().addTo(mymap);
            ctlAttribute.addAttribution('OSM');


            ctlScale = L.control.scale({
                position: 'bottomleft',
                metric: false,
                maxWidth: 200
            }).addTo(mymap);

            ctlMouseposition = L.control.mousePosition().addTo(mymap);

            ctlStyle = L.control.styleEditor({
                topright: 'bottomleft',
                openOnLeafletDraw: false
            }).addTo(mymap);

            ctlMeasure = L.control.polylineMeasure().addTo(mymap);

            /*Layer Intialization*/
            /*Layer Basemaps*/
            lyrOSM = L.tileLayer.provider('OpenStreetMap.Mapnik');
            lyrTopo = L.tileLayer.provider('OpenTopoMap');
            lyrImagery = L.tileLayer.provider('Esri.WorldImagery');
            console.log('Astaga');
            lyrOutdoors = L.tileLayer.provider('Thunderforest.Outdoors');
            lyrWatercolor = L.tileLayer.provider('Stamen.Watercolor');
            mymap.addLayer(lyrOSM);

            fgpDrawnitems = new L.FeatureGroup();
            fgpDrawnitems.addTo(mymap);

            /*Layer Utama*/

            /*Layer Sekolah*/
            lyrSekolah = L.geoJSON.ajax('data/Sekolah.geojson', {
                pointToLayer: returnSekolahMarker,
                filter: filterSekolah
            }).addTo(mymap);

            lyrSekolah.on('data:loaded', function() {
                arSekolahIDs.sort(function(a, b) {
                    return a - b
                });
                $("#txtFindSekolah").autocomplete({
                    source: arSekolahIDs
                });
            });

            /*Layer Batas Administrasi*/
            lyrAdministrasi = L.geoJSON.ajax('data/Administrasi.geojson', {
                style: styleAdministrasi
            }).addTo(mymap);
            lyrAdministrasi.on('data:loaded', function() {});

            /*Layer Jalan*/
            lyrJalan = L.geoJSON.ajax('data/Jalan.geojson', {
                style: styleJalan,
                // onEachFeature: processJalan,
                // filter: filterJalan
            }).addTo(mymap);

            lyrJalan.on('data:loaded', function() {
                arJalanIDs.sort(function(a, b) {
                    return a - b
                });
                $("#txtFindJalan").autocomplete({
                    source: arJalanIDs
                });
            });

            /*Layer Landuse*/
            lyrLanduse = L.geoJSON.ajax('data/Pertanian.geojson', {
                style: styleLanduse
            }).addTo(mymap);
            lyrLanduse.on('data:loaded', function() {});

            /*Setup Layer Control*/
            objBasemaps = {
                "Open Street Maps": lyrOSM,
                "Topo Map": lyrTopo,
                "Imagery": lyrImagery,
                "Outdoors": lyrOutdoors,
                "Watercolor": lyrWatercolor,
            };

            objOverlays = {
                "Sekolah": lyrSekolah,
                "Batas Administrasi": lyrAdministrasi,
                "Jalan": lyrJalan,
                "Landuse": lyrLanduse
            };

            ctlLayers = L.control.layers(objBasemaps, objOverlays).addTo(mymap);
            mymap.on('overlayadd', function(e) {
                var strDiv = "#lgnd" + e.name;
                $(strDiv).show();
            });

            mymap.on('overlayremove', function(e) {
                var strDiv = "#lgnd" + e.name;
                $(strDiv).hide();
            });

            //****Location Event****//
            mymap.on('Locationfound', function(e) {
                console.log(e);
                if (mrkCurentLocation) {
                    mrkCurentLocation.remove()
                }
                mrkCurentLocation = L.circle(e.latlng, {
                    radius: e.accuracy / 2
                }).addTo(mymap);
                mymap.setView(e.latlng, 14);
            });

            mymap.on('locationerror', function(e) {
                console.log(e);
                alert("location was not found");
            });

            /*Function*/
            /*Sekolah Function*/

            $("#btnSekolah").click(function() {
                $("#lgndSekolahDetail").toggle();
            });

            $("#btnAdministrasi").click(function() {
                $("#lgndAdministrasiDetail").toggle();
            });

            $("#btnLanduse").click(function() {
                $("#lgndLanduseDetail").toggle();
            });

            $("#btnJalan").click(function() {
                $("#lgndJalanDetail").toggle();
            });

            // $("#btnAdministrasi").click(function() {
            //     $("#lgndAdministrasiDetail").toggle();
            // });

            function returnSekolahMarker(json, latlng) {
                var att = json.properties;
                if (att.tipe == 'SMK') {
                    var clrSekolah = 'deeppink';
                } else {
                    if (att.tipe == 'SMA') {
                        var clrSekolah = 'lightgreen';
                    } else {
                        if (att.tipe == 'MA') {
                            var clrSekolah = 'Blue';
                        } else {
                            var clrSekolah = 'lightgreen';
                        }
                    }
                }
                return L.circleMarker(latlng, {
                    radius: 7,
                    color: clrSekolah
                }).bindTooltip(
                    "<h4>sekolah: " +
                    att.Name +
                    "</h4>Satuan: " +
                    att.tipe
                );
            }

            function filterSekolah(json) {
                var att = json.properties;
                var optFilter = $("input[name=filterSekolah]:checked").val();
                if (optFilter == 'ALL') {
                    return true;
                } else {
                    return (att.tipe == optFilter);
                }
            }

            $("#txtFindSekolah").on('kyup paste', function() {
                var val = $("#txtFindSekolah").val();
                testLayerAttribute(arSekolahIDs, val, "ID Sekolah", "#divFindSekolah", "#divSekolahError", "#btnFindRumah");
            });

            $("#btnFindSekolah").click(function() {
                var val = $("#txtFindSekolah").val();
                var lyr = returnLayerByAttribute(lyrSekolah, 'famcard_id', val);
                if (lyr) {
                    if (lyrSearch) {
                        lyrSearch.remove();
                    }
                    lyrSearch = L.cirle(lyr.getLatLng(), {
                        radius: 10,
                        color: 'red',
                        weight: 10,
                        opacity: 0.5,
                        fillOpacity: 0
                    }).addTo(mymap);
                    mymap.setView(lyr.getLatLng(), 25);
                    var att = lyr.feature.properties;
                    $("#divSekolahData").html("<h4 class='text-left'>Keterangan</h4><h5>Status Sekolah: " + att.status + "</h5><h5>Alamat:" + att.alamat + "</h5><h5><Nama Kepala Keluarga:" + att.nam_kk + "</h5><h5>Jenis Kelamin: " + att.jenkel + "</h5><h5>Umur:" + att.umur + "</h5><h5>Pendidikan:" + att.pendidikan + "</h5><h5>Perkerjaan: " + att.perkerjaan + "</h5>");
                    console.log('Mantap');
                    $("#divSekolahError").html("");
                    fgpDrawnItems.clearLayers();
                    fgpDrawnItems.addLayer(lyr);

                } else {
                    $("#divSekolahError").html("**** Sekolah Tidak Ditemukan ****");
                }
            });
            $("#labelSekolah").click(function() {
                $("#divSekolahData").toggle();
            });

            $("input[name=filterSekolah]").click(function() {
                arSekolahlIDs = [];
                lyrSekolah.refresh();
            });

            function processJalan(json, lyr) {
                var att = json.properties;
                lyr.bindTooltip("<h4>Jalan:" + att.JALAN + "<br>Length:" + returnMultiLength(lyr.getLatLngs()).toFixed(0));
                arJalanIDs.push(att.JALAN.toString());
            }

            function filterJalan(json) {
                var arProjectFilter = [];
                $("input[name=Project]").each(function() {
                    if (this.checked) {
                        arJalanFilter.push(this.value);
                    }
                });
                var att = json.properties;
                switch (att.type) {
                    case "jalan Kolektor":
                        return (arProjectFilter.indexOf('jalan Kolektor') >= 0);
                        break;
                    case "Jalan Setapak":
                        return (arProjectFilter.indexOf('Jalan Setapak') >= 0);
                        break;
                    case "Jalan Lokal":
                        return (arProjectFilter.indexOf('jalan Lokal') >= 0);
                        break;
                    case "jalan Lain":
                        return (arProjectFilter.indexOf('jalan Lain') >= 0);
                        break;
                }
            }

            function styleAdministrasi(json) {
                // var att = json.properties;
                // switch (att.BATAS) {
                //     case 'Batas Prov':
                //         return {
                //             color: '#C71585', weight: "5", dashArray: "10,7,1"
                //         };
                //         break;
                //     case 'Batas Kabu':
                //         return {
                //             color: '#2bdf94', weight: "3", dashArray: "10,7,1,7,1,7"
                //         };
                //         break;
                //     case 'Batas Keca':
                //         return {
                //             color: '#351c75', weight: "2,5", dashArray: "10,7,1,7,1,7,1,7"
                //         };
                //         break;
                //     case 'Batas Desa':
                //         return {
                //             color: '#f1c232', weight: "1,5", dashArray: "10,7,1,7,1,7,1,7,1,7"
                //         };
                //         break;
                // }
                return {
                            color: '#C71585', weight: "5", dashArray: "10,7,1"
                        };
            }

            function styleJalan(json) {
                var att = json.properties;
                switch (att.JALAN) {
                    case 'Jalan Kolektor':
                        return {
                            color: 'Red', weight: "3", dashArray: "10,7,1"
                        };
                        break;
                    case 'Jalan Setapak':
                        return {
                            color: 'Orange', weight: "2,5", dashArray: "10,7,1"
                        };
                        break;
                    case 'Jalan Lokal':
                        return {
                            color: 'Blue', weight: "2", dashArray: "10,7,1"
                        };
                        break;
                    case 'Jalan Lain':
                        return {
                            color: 'deeppink', weight: "1,5", dashArray: "10,7,1"
                        };
                        break;
                }
            }

            function styleLanduse(json) {
                var att = json.properties;
                switch (att.Jenis) {
                    case 'Sawah':
                        return {
                            color: '#FFA500', weight: "0", fillOpacity: "0.7"
                        };
                        break;
                    case 'Kebun':
                        return {
                            color: '#00FFFF', weight: "0", fillOpacity: "0.7"
                        };
                        break;
                    case 'Ladang':
                        return {
                            color: '#A52A2A', weight: "0", fillOpacity: "0.7"
                        };
                        break;
                }
            }

            function returnLayerByAttribute(lyr, att, val) {
                var arLayers = lyr.getLayers();
                for (i = 0; i < arLayers.lenght - 1; i++) {
                    var ftrVal = arLayers[i].feature.properties[att];
                    if (ftrVal == val) {
                        return arLayers[i];
                    }
                }
                return false;
            }

        });
    </script>
</body>

</html>