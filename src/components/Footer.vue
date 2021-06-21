<template>
  <div class="footer_container">

    <div class="footer_top">

      <div class="footer_logo_left">
        <img src= "../assets/img/medical_logo_2x_dark.png" alt="logo">
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Repellat rem soluta qui eligendi eos? Non eaque, blanditiis, inventore voluptas dolorum, nulla rerum animi provident voluptatem expedita in. Deserunt voluptate corrupti quis dolorum </p>
        <h5>LEARN MORE ABOUT US</h5>
        <ul>
          <li>
            <a href="#">
              <i class="fab fa-instagram-square instagram"></i>
              <i class="fab fa-facebook-square facebook"></i>
              <i class="fab fa-youtube-square you_tube"></i>
              <i class="fab fa-twitter-square twitter"></i>
            </a>
          </li>
        </ul>
      </div>

      <div class="footer_contact">
        <h4>CONTACT INFORMATION</h4>
        <ul>
          <li>
            <a href="#">
              <i class="fas fa-map-marker-alt"></i>
              <span>121 king street,london united kingdom</span>
            </a>
          </li>
          <li>
            <a href="#">
              <i class="fas fa-phone"></i>
              <span>1.800.458.556</span>
            </a>
          </li>
        </ul>
      </div>

      <div class="footer_medical">
        <h4>MEDICAL DEPARTMENTS</h4>
        <ul>
          <li>
            <img src="../assets/img/play-icon.png" alt="">
            <a href="#">
              Cardiology
            </a>
            <li>
            <img src="../assets/img/play-icon.png" alt="">
            <a href="#">
              Pediactris
            </a>
            <li>
            <img src="../assets/img/play-icon.png" alt="">
            <a href="#">
              Diabetsa Care
            </a>
            <li>
            <img src="../assets/img/play-icon.png" alt="">
            <a href="#">
              Pre natel care
            </a>
          </li>
           <li>
            <img src="../assets/img/play-icon.png" alt="">
            <a href="#">
              Ultrasound echocardiogram
            </a>
          </li>
        </ul>
        <button>
          WIEW OUR DEPARTMENTS
        </button>
      </div>

    </div>

    <div class="footer_bottom">
      <span>Copyright 2012/2020</span>
      <span>Avada Theme by Theme fusion</span>
      <span>All rights reserved</span>
      <span>Powered by WordPress</span>
    </div>

  </div>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style lang="scss" scoped>


.footer_top {
  display: flex;
  justify-content: space-around;
}

.footer_logo_left {
  width: 300px;
  margin-left: 20px;

  h5 {
    margin-top: 10px;
    border-top: 1px solid black;
  }

  p {
    font-size: 13px;
    padding-bottom: 10px;
    padding-top: 10px;
  }

  ul {
    padding-left: 0;
    padding-top: 10px;

      li {
      list-style: none;

          i {
          margin: 10px;

         
        }
    }
  }
}

img {
    height: 40px;
    padding-left: 10px;
    padding-top: 15px;
}

.facebook {
    color: blue;
}

.instagram {
  color: dodgerblue;
}

.you_tube {
  color: red;
}

.twitter {
  color: #449ebf;
}

.footer_contact {
    
    h4 {
      padding-top: 15px;
      border-bottom: 1px solid dodgerblue;
      padding-bottom: 10px;
    }

    ul{
      padding-left: 0;

        li {
          list-style: none;
          padding-top: 10px;
          a {
            text-decoration: none;

              span {
                color: black;
              }
          }

          i {
            color: dodgerblue;
            padding-right: 5px;
          }
        }
    }

}

.footer_medical {
  h4 {
      padding-top: 15px;
      border-bottom: 1px solid dodgerblue;
      padding-bottom: 10px;
  }

  img {
    height: 30px;
  }

  ul {
    padding-left: 0;

    li {
      list-style: none;
      padding-top: 10px;

        a {
          text-decoration: none;
          color: black;
        }
    }
  }

  button {
    background-color: white;
    border: 2px solid grey;
    margin-top: 25px;
    padding: 6px;
  }
}

.footer_bottom {
  margin-top: 10px;
  background-color: lightgray;
  height: 50px;
  line-height: 50px;

    span {
      border-right: 1px solid grey;
      padding-right: 10px;
      padding-left: 5px;
    }
}

</style>