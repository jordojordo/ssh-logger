<template>
  <div>
    {{ configString }}
  </div>
</template>

<script>
import SSHConfig from "ssh-config";

const config = SSHConfig.parse(`
    IdentityFile ~/.ssh/id_rsa
  `);

const configString = SSHConfig.stringify(config);



export default {
  name: "sshReader",
  data: function() {
    return {
      configString: configString,
    };
  },
};
</script>
