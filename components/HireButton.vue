<template>
    <div>
        <div class="primary-hire-button">
            <div class="wrapper">
                <button class="hire-button">Hire Me .</button>
            </div>
        </div>
        <div class="secondary-hire-button">
            <div class="row align-items-center">
                <div class="col-2 p-0"><hr style="background-color: white; height: 1px;"></div>
                <div class="col-8 p-0">
                    <div class="wrapper">
                        <button class="hire-button">Hire Me .</button>
                    </div>
                </div>
                <div class="col-2 p-0"><hr style="background-color: white; height: 1px;"></div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .hire-button{
        font-family: 'Poppins';
        padding: 16px 30px;
        background-color: white;
        color: black;
        border: none;
        font-size: 16px;
        font-weight: 600;
    }

    .secondary-hire-button{
        display: none;
    }

    
  @media (max-width: 575.98px) {
    .wrapper{
        text-align: center;
    }

    .primary-hire-button{
        display: none;
    }

    .secondary-hire-button{
        display: inline;
    }

  }

  @media (max-width: 991.98px) {
    .wrapper{
        text-align: center;
    }

    
    .primary-hire-button{
        display: none;
    }
    
    .secondary-hire-button{
        display: inline;
    }
  }
</style>