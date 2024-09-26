# Ecommerce-Website-Products-Section
# This repository is about a responsive web page created using HTML, CSS and bootstrap
# HTML code
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <h1>Our Products</h1>
    <div class="container">
        <div class="row">
            <div class="col-12 col-sm-12 col-md-6">
                <div class="bg-img1 d-flex flex-column justify-content-end mb-3">
                    <h2>Smart Headphones</h2>
                    <p class="paragraph">Headphones with Deep Bass, sound, touch...</p>
                    <button type="button" class="button2" data-toggle="modal" data-target="#exampleModal">View More</button>
                    <div class="modal fade" id="smartHeadphonesModel" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                        <div class="modal-dialog">
                            <div class="modal-content">
                                <div class="modal-header">
                                    <h5 class="modal-title" id="exampleModalLabel">Sony WH-1000XM4 Noise Cancelling Headphones</h5>
                                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                                        <span aria-hidden="true">&times;</span>
                                    </button>
                                </div>
                                <div class="modal-body">
                                    <h6>Get Best Smart Headphones Prices Online in India. Select from the best range of Headphones from most popular brands...</h6>
                                    <h4>Voice Assistant:<span> Alexa, Google Assistant & Siri</span></h4>
                                    <h4>Smart listening:<span> Ambient sound with the best noise cancellation</span></h4>
                                    <h4>Long battery life:<span> A single charge provides 30 hours of playtime</span></h4>
                                    <h4>Quick charging:<span> Charge for 10 min for 5 hours play back</span></h4>
                                </div>
                                <div class="modal-footer">
                                    <button type="button" class="button-headphone" data-dismiss="modal">Buy Now</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-12 col-sm-12 col-md-6">
                <div class="bg-img2 d-flex flex-column justify-content-end mt-3">
                    <h2>Laptops</h2>
                    <p class="paragraph">Explore vast selection of Laptops...</p>
                    <button type="button" class="button2" data-toggle="modal" data-target="#exampleModal">View More</button>
                    <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                        <div class="modal-dialog">
                            <div class="modal-content">
                                <div class="modal-header">
                                    <h5 class="modal-title" id="laptopModalLabel">Inspiron 14 5490 core i5 Laptop</h5>
                                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                                        <span aria-hidden="true">&times;</span>
                                    </button>
                                </div>
                                <div class="modal-body">
                                    <h6>Get Best Laptop Prices Online in India. Select from the best range of Laptops from most popular brands...</h6>
                                    <h4>Performance:<span>Core i5 3rd Gen, 2.6 Ghz, 4GB RAM</span></h4>
                                    <h4>Storage:<span>500 GB HDD, SATA, 7200 RPM</span></h4>
                                    <h4>Battery: <span>Li-lon, 6 Cell</span></h4>
                                    <h4>Design: <span>14.0 Inches, 1366 X 768, 2.07 Kg. 34 Mm Thick</span></h4>
                                </div>
                                <div class="modal-footer">
                                    <button type="button" class="button-headphone" data-dismiss="modal">Buy Now</button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="d-flex flex-row justify-content-end">
        <a href="See All Offers" class="color-href">See All Offers<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="orange" class="bi bi-arrow-right-short" viewBox="0 0 16 16">
                <path fill-rule="evenodd" d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8z" />
            </svg></a>
    </div>
</body>

</html>
