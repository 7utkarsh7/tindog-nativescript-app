

<template>
<Page actionBarHidden="true">

  <FlexboxLayout class="page">

    <StackLayout class="form">
      <Label text="tindog" class="header" />


        <TextField class="input-field1" text="Username" />


        <TextField class="input-field2" secure="true" text="password" />

      <Button text="New User? Register" tap="submit" class="btn btn-primary btnLogin" />
      <Button text="Login Instead" tap="submit" class=" btn-secondary" />

        <Label text="copyright tindog 2020" class="footer" />

    </StackLayout>
  </FlexboxLayout>
</Page>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>

<style>
.page {
  align-items: center;
  background-color: #f5f5f5;
  vertical-align: center;
  height: 100%;
}

.form {
  vertical-align: center;
  width: 100%;
  margin-left: 10;
  margin-right: 10;
  background-color: #f5f5f5;
}

.header {
  font-size: 40;
  text-align: center;
  color: #000;
  font-weight: 600;
  margin-bottom: 40;
}

.input-field1 {
  margin-top: 10;
  margin-bottom: -5;
  box-sizing: border-box;
  color: #dddddd;
  color: #dddddd;
  z-index: 2;
  font-size: 22;
  background-color: #fff;
  border-top-left-radius: 6;
  border-top-right-radius: 6;
  border-bottom-left-radius: 6;
  border-bottom-right-radius:
    6;
  border-block-end-color: gray;
}

.input-field2 {
  margin-bottom: 30;
  color: #dddddd;
  color: #dddddd;
  z-index: 2;
  font-size: 22;
  background-color: #fff;
  border-bottom-left-radius:
    6;
  border-bottom-right-radius: 6;
  border-top-left-radius: 6;
  border-top-right-radius: 6;
}



.btnLogin {
  background-color: #fbd46d;
  margin-left: 10;
  margin-right: 10;
  font-size: 16;
}

.footer {
  text-align: center;
  margin-top: 1;
  color: gray;
}
</style>
