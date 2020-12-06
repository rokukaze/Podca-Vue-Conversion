<template>
          <div class="col-md-6 col-lg-4 mb-5 mb-lg-5">
            <div class="team-member">

              <img :src="imageSource" alt="Image" class="img-fluid">

              <div class="text">

                <h2 class="mb-2 font-weight-light h4">{{teamMemberName}}</h2>
                <span class="d-block mb-2 text-white-opacity-05">{{teamMemberTitle}}</span>
                <p class="mb-4">{{teamMemberDescription}}</p>
                <p>
                  <a href="#" class="text-white p-2"><span class="icon-facebook"></span></a>
                  <a href="#" class="text-white p-2"><span class="icon-twitter"></span></a>
                  <a href="#" class="text-white p-2"><span class="icon-linkedin"></span></a>
                </p>
              </div>

            </div>
          </div> 
</template>

<script>
export default {
  name: 'BehindTheMicTeamMember',
  props:{
      imageSource: {
          type: String,
          default: "images/defaultavatar.png"
      },
      teamMemberName: {
          type: String,
          default: "John Doe"
      },
      teamMemberTitle: {
          type: String,
          default: "Podcast Member"
      },
      teamMemberDescription: 
      {
          type: String,
          default: "Lorem Ipsum"
      }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
