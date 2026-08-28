<template>
  <div class="login container-fluid h-100 p-0 d-flex">
    <div class="background w-50"></div>
    <div
      class="d-flex login-form w-50 justify-content-center align-items-center"
      id="example"
    >
      <div class="card w-50 p-3">
        <div class="card-body">
          <form class="row validation">
            <div class="col-12 input-group input-group-lg pb-4">
              <span class="input-group-text" id="inputGroup-sizing-lg">帳號</span>
              <input
                type="text"
                class="form-control"
                aria-label="Sizing example input"
                aria-describedby="inputGroup-sizing-lg"
              />
            </div>
            <div class="col-12 input-group input-group-lg pb-4">
              <span class="input-group-text" id="inputGroup-sizing-lg">密碼</span>
              <input
                type="password"
                class="form-control"
                aria-label="Sizing example input"
                aria-describedby="inputGroup-sizing-lg"
              />
            </div>
            <div class="d-flex justify-content-center col-12 button-area">
              <button type="button" class="btn btn-primary">登入</button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>
<script lang="ts" setup></script>
