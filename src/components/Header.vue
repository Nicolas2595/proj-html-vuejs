<template>
  <div class="header_container">

      <div class="link_header_container">
          <div class="header_logo">
              <img src="../assets/img/medical_logo_1x_light.png" alt="logo">
          </div>

          <div class="header_link">
              <ul>
                  <li>
                      <a href="#" class="active">Home</a>
                  </li>
                   <li>
                      <a href="#">About</a>
                  </li>
                   <li>
                      <a href="#">Departments</a>
                  </li>
                   <li>
                      <a href="#">Articles</a>
                  </li>
                   <li>
                      <a href="#">Make Appointment</a>
                  </li>
              </ul>
          </div>
          
      </div>

        <div class="central_header wrapper_60">
              <h1>Caring <span>For Life</span></h1>
              <p>Kind words can be short and easy to speak, but their echoes are truly endless. Avada health focuses on you as if it was our own family</p>
              <button>
                  Learn More
              </button>
        </div>

  </div>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style lang="scss" scoped>

.header_container {
    background: url('../assets/img/header-image-homepage.jpg');
    height: 600px;
    width: 100%;
    background-size: 100%;
    background-repeat: no-repeat;
    background-position: top bottom;

    .link_header_container {
        display: flex;
        justify-content: space-between;

        .header_link {

            padding-top: 15px;
            padding-right: 15px;
              
            ul {
                 display: flex;

                li {

                    list-style: none;

                    a{
                        text-decoration: none;
                        color: white;
                        font-size: 15px;
                        margin-right: 10px;
                    }

                    &:last-child {
                            background-color: #3ba5bd;
                            padding: 2px;
                        }

                    .active {
                        color: #3ba5bd;
                    }
                }
            }
        }
     
    }

    .header_logo {

        img {
            height: 40px;
            padding-left: 15px;
            padding-top: 15px;
        }
    }

    .central_header {

        margin-top: 100px;

        h1 {
            color: white;
            margin-bottom: 15px;
             span {
            color: #3ba5bd;
            }
        }

        p {
            color: white;
            width: 400px;
            margin-bottom: 15px;
            font-size: 13px;
        }

        button {
            padding: 8px;
            width: 150px;
            background-color: #3ba5bd;
            border: none;
            color: white;
            cursor: pointer;
        }
       
    }

    
}

</style>