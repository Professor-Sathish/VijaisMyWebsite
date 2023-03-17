<script lang="ts">

// my skillset
const skills = ['Design', 'Mobile Development', 'Fullstack Development', 'Wireframing', 'Interaction Design']

// my social link
const links = [{
    name: 'Twitter',
    url: 'https://www.twitter.com/spikeysanju'
},
{
    name: 'Instagram',
    url: 'https://www.twitter.com/spikeysanju',
    icon: 'https://png.pngtree.com/png-vector/20221018/ourmid/pngtree-instagram-icon-png-image_6315974.png'
}, {
    name: 'Facebook',
    url: 'https://www.facebook.com/spikeysanju',
    icon: 'https://img.freepik.com/premium-vector/blue-social-media-logo_197792-1759.jpg?w=2000'
}]

</script>

<h1 class='text-xl sm:text-5xl'>Hello Foss</h1>





<div class='p-4 space-y-3'>
    <img class='rounded-full w-32 h-32 border-4 border-red-500 shadow-2xl' src="https://avatars.githubusercontent.com/u/23400022?v=4" alt="Headshot of Sanju">
    <h1 class='text-black text-md sm:text-6xl font-semibold'>Chole Zimmer</h1>
    <p class='text-gray-500'>A design is a plan or specification for the construction of an object or system or for the implementation of an activity or process or the result of that plan or specification in the form of a prototype, product, or process.</p>
</div>


<div class="w-fit hover:cursor-pointer hover:border-yellow-500 rounded-lg border border-yellow-200 bg-yellow-50 p-6 flex flex-col space-y-4">
  
    <div class=' space-y-2'>
 
        <img class='rounded-xl border-4 w-16 h-16 shadow-xl' src="https://avatars.githubusercontent.com/u/23400022?v=4" alt="Headshot of Sanju">
        <h5 class=' text-lg font-medium'>John Wick</h5>
        <a class=' text-gray-500' href="https://www.john.com">https://www.john.com</a>

    </div>

    <button class=" w-fit rounded-full bg-violet-500 text-white px-3 py-[1.5px]">Support</button>
</div>

<!-- 

{#each skills as item}
     <p> {item}</p>
{/each}

<h3>My Social Handles</h3>

{#each links as item}
<h5>{item.name}</h5>
<a href={item.url}>{item.url}</a>
{/each}
 -->
