<script lang="ts">
/* https://docs.aws.amazon.com/prescriptive-guidance/latest/best-practices-cdk-typescript-iac/typescript-best-practices.html */
/* https://github.com/bevacqua/dragula/issues/602#issuecomment-477734315 */
if (typeof (window as any).global === "undefined") {
  (window as any).global = window;
}
</script>

<script lang="ts" setup>

</script>

<template>
  <client-only>
    <div class="az-main">
      <div class="copyright">&copy; 2024 <a href="https://github.com/rmaniego/" class="profile leckerli-one">Rydeon <span class="emoji1">⚡</span><span class="emoji2">✨</span></a></div>
    </div>
  </client-only>
</template>

<style scoped>
* {
  box-sizing: border-box;
}

.copyright {
	position: fixed;
  left: 0;
	bottom: 0;
	padding: 10px; 
	width: 100%;
	color: rgba(255, 255, 255, 0.7);
  font-family: Arial, Helvetica, sans-serif;
	text-align: center;
	font-size: 0.7em;
}

.profile {
	padding: 3px 5px 3px 8px;
	color: #fff;
	background-color: #382f66;
  font-family: "Leckerli One", cursive;
  font-weight: 400;
  font-style: normal;
	text-decoration: none;
	border-radius: 8px;
}

.profile:hover {
	color: #111 !important;
	background-color: #e1b403 !important;
	-webkit-box-shadow: 0px 0px 5px 0px rgba(204,180,0,1);
	-moz-box-shadow: 0px 0px 5px 0px rgba(204,180,0,1);
	box-shadow: 0px 0px 5px 0px rgba(204,180,0,1);
	transition: color 0.5, background-color 0.5s, box-shadow 0.5s;
}

.emoji1 {
	margin-left: -3px;
}

.emoji2 {
	margin-left: -6px;
}

@media only screen and (max-width: 500px) {

  .copyright {
    margin-bottom: 25px;
  }
}

</style>
