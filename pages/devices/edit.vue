<template>
  <div>
  <div role="group">
    <label for="inputLive">Name:</label>
    <b-form-input id="inputLive"
                  v-model.trim="name"
                  type="text"
                  :state="nameState"
                  aria-describedby="inputLiveHelp inputLiveFeedback"
                  placeholder="Enter device name"></b-form-input>
    <b-form-invalid-feedback id="inputLiveFeedback">
      Enter at least 3 letters
    </b-form-invalid-feedback>
    <b-form-text id="inputLiveHelp">
      Enter name to help you remember this device
    </b-form-text>
  </div>

  <div role="group">
    <label for="inputLive">Identifier:</label>
    <b-form-input id="inputLive"
                  v-model.trim="name"
                  type="text"
                  :state="nameState"
                  aria-describedby="inputLiveHelp inputLiveFeedback"
                  placeholder="Enter device identifier"></b-form-input>
    <b-form-invalid-feedback id="inputLiveFeedback">
      Enter at least 3 letters
    </b-form-invalid-feedback>
    <b-form-text id="inputLiveHelp">
      Enter the Id assigned to the device
    </b-form-text>
  </div>  

  </div>
</template>
