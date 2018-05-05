<template>
    <div class="container">
        <!-- pass quote in there -->
        <!-- because expect quotes in the props -->
    <app-quote-grid :quotes="showQuotes">
    </app-quote-grid>    
    </div>
</template>

<script>

    import QuoteGrid from './components/QuoteGrid.vue'; 
    export default {
        data: function(){
            return{
                // the maximum number of quote cards number
                maxQuotes: 10,
                // initialize quote content
                showQuotes:[
                    'write something'
                ]
            }
        },
        components: {
                appQuoteGrid: QuoteGrid
        }
        
    }
</script>

<style>
</style>
