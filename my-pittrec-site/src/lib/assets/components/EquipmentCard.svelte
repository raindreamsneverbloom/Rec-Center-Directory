<script lang="ts">
    export let name: string;
    export let locations: 
    {floor:string;
        variants:{type:string;quantity:number}[];}[]=[];
</script>


<div class="border rounded p-4 mb-6 bg-white shadow">
  <h2 class="text-xl font-semibold mb-2">{name}</h2>
  <ul class="list-disc list-inside space-y-1">
    {#each locations as loc}
      <li>
        {loc.floor} has
        {#each loc.variants as variant, i}
            {variant.quantity} {variant.type}
            {variant.quantity === 1 ? '' : 's'}
            {i < loc.variants.length - 2 ? ',' : ''}
            {i === loc.variants.length - 2 ? ', and' : ''}
        {/each}
        </li>
    {/each}
  </ul>
</div>