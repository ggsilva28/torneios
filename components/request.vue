<script>
    const axios = require('axios').default;
    const url = 'https://my-json-server.typicode.com/ggsilva28/torneios'

    axios.get(url + '/usuarios')
        .then(function(response) {
            // handle success
            console.log(response);
        })
</script>