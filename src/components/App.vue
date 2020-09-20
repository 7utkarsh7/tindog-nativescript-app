<template>
<Page actionBarHidden="true">


            <FlexboxLayout class="page1">

                <StackLayout class="form1">
                    <Label text="Welcome to " />
                    <Label text="tindog!" class="header1" />

                    <Button text="Get Started" @tap="btnTap"
                        class="btn btn-primary btnStart" />
                </StackLayout>
            </FlexboxLayout>
    </Page>



</template>

<script >
import Login from "./Login";

  export default {
      components: {
          Login
      },
      methods: {
          btnTap(args) {
              this.$navigateTo(Login);
          }
      }
  };
</script>

<style scoped>
.page1 {
    align-items: center;
    background-color: #f5f5f5;
    vertical-align: center;
    height: 100%;
    width: 100%;
    text-align: center;
}

.btnStart {
    margin-left: 100;
    margin-right: 100;

}

.header1 {
    font-size: 50;
    text-align: center;
    color: #000;
    font-weight: 800;
    margin-bottom: 40;
    width: 100%;
}
</style>
