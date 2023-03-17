<script lang="ts">

// my skillset
const skills = ['Professor', 'Mobile Development', 'Fullstack Development', 'Wireframing', 'Interaction Design']

// my social link
const links = [{
    name: 'Twitter',
    url: 'https://www.twitter.com/spikeysanju'
},
{
    name: 'Instagram',
    url: 'https://www.twitter.com/spikeysanju'
}, {
    name: 'Facebook',
    url: 'https://www.facebook.com/spikeysanju'
}]

</script>


<img src="https://avatars.githubusercontent.com/u/23400022?v=4" alt="Headshot of Sanju">
<h1>Sathish Kumar</h1>
<p>A design is a plan or specification for the construction of an object or system or for the implementation of an activity or process or the result of that plan or specification in the form of a prototype, product, or process.</p>


{#each skills as item}
     <p> {item}</p>
{/each}

<h3>My Social Handles</h3>

{#each links as item}
<h5>{item.name}</h5>
<a href={item.url}>{item.url}</a>
{/each}
