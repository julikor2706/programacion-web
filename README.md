    body {
        height: 100vh;
        display: flex;
        flex-direction: column; 
        align-items: center;
        justify-content: center;
        background-image: url('descarga (2).jpg'); 
        background-size: cover; 
        background-position: center;
    }

    h1 {
        margin-bottom: 20px; 
        font-size: 2em; 
        color: #ebe9e9;
        text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.7); 
    } 

    .carousel {
        position: relative;
        width: 600px;
        height: 400px;
        overflow: hidden;
        background-color: rgba(75, 7, 75, 0.8); 
        border-radius: 10px; 
    }

    .slider-section {
        display: none;
        width: 100%;
        height: 100%;
    }

    .slider-section img {
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

    .btn-left, .btn-right {
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        background-color: rgba(160, 127, 127, 0.7);
        border: none;
        padding: 10px;
        cursor: pointer;
    }

    .btn-left {
        left: 10px;
    }

    .btn-right {
        right: 10px;
    }
</style>
