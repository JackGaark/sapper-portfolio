<script>
    import Carousel from '@beyonk/svelte-carousel'
    import { onMount } from 'svelte'

    let sliders = [
      {
        title: '',
        node: null,
        images: [
          {
            title: 'example',
            url: '/images/Projects/project1/1.jpg'
          },
          {
            title: 'example',
            url: '/images/Projects/project1/2.jpg'
          },
          {
            title: 'example',
            url: '/images/Projects/project1/3.jpg'
          },
          {
            title: 'example',
            url: '/images/Projects/project1/main.jpg'
          }
        ],
      }
    ]

    onMount( () =>  {
        
      }
    )
</script>
{#each sliders as slider }
<div bind:this={slider.node}>



<Carousel perPage=1>
    <span class="control" slot="left-control">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
            <path fill-rule="evenodd" d="M12.707 5.293a1 1 0 010 1.414L9.414 10l3.293 3.293a1 1 0 01-1.414 1.414l-4-4a1 1 0 010-1.414l4-4a1 1 0 011.414 0z" clip-rule="evenodd"/>
          </svg>
    </span>

    {#each slider.images as image}
      <div class="slide-content">
        <img src={image.url} alt={image.title}/>
      </div>
    {/each}

    <span class="control" slot="right-control">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor">
        <path fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd"/>
      </svg>
    </span>
  </Carousel>
</div>
  {/each}

    <style>

        .slide-content {
            height: 90vh;
            justify-content: center;
            place-items: center;
            display: flex;
            
        }

      .control :global(svg) {
          width: 100%;
          height: 100%;
          color: #fff;
          border: 2px solid #fff;
          border-radius: 32px;
        }
    </style> 