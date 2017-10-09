<template>
  <social-sharing url="https://vuejs.org/"
        title="The Progressive JavaScript Framework"
        description="Intuitive, Fast and Composable MVVM for building interactive interfaces."
        quote="Vue is a progressive framework for building user interfaces."
        hashtags="vuejs,javascript,framework"
        twitter-user="vuejs"
        :networkList="['facebook','twitter','email']"

        >
      <div slot="email">
          <i class="fa fa-envelope"></i> Email
      </div>
      <div slot="facebook">
        <i class="fa fa-facebook"></i> Facebook
      </div>
  </social-sharing>
</template>
<script>
import SocialSharing from '../src'
export default {
    components:{SocialSharing}
}
</script>
