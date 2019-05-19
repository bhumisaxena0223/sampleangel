<template>
    <div id="home">
         <b-container fluid class="container bg-white padding shadow rounded">
            <b-row>
                <b-col class="m-1 bg-white p-3">
                    <b-container class="bv-example-row">
                        <b-row>
                            <b-col> 
                                <h2>
                                    ATS Hamlet
                                </h2>
                            </b-col>
                        </b-row>
                     </b-container>
                </b-col>
                <b-col class="text-right side">
                    <b-button class="filter" size="sm" v-b-toggle.collapse-1 variant="outline-primary">
                            <i class="fas fa-bars"></i>
                    </b-button>
                </b-col>
            </b-row>
            <b-row class="p-3 img-div">
                <b-col cols="7" md="7" sm="7" >
                    <img src="https://homepages.cae.wisc.edu/~ece533/images/fruits.png" width="100%" height="45%"/>
                </b-col>
                <b-col md="4" sm="4" cols="4" class="text-justify" style="margin-left:20px;">
                    <h3 class="sub-head">Rs 30 - 33 Lacs</h3>
                    <p class="">Sector 118, Noida</p>
                    <span>Configs:</span>
                    <p class="">{{values.configs}}</p>
                    <span>Property Status:</span>
                    <p>{{values.propertyStatus}}</p> 
                    <b-button class="view" >View Property</b-button>
                </b-col>
            </b-row>
         </b-container>
    </div>
</template>

<script>

export default {
    name: 'Home',
    data () {
        return{
            values:{ 
                configs: "3 BHK | Apartments | 300sqft",
                propertyStatus:  "Resale (Currently Occupied)"
            }
        }
    }
}

</script>

<style scoped>
.side{
    margin-top:15px;
}
.sub-head {
    border-bottom: 3px grey solid;
    width: 80%;
    line-height: 2;
}
p{
    font-weight: 600;
    font-size: 20px;
}
.view{
    float: right;
    border-radius: 0%;
    background-color: #ea68ce;
    border: none;
}
.img-div{
    height: 370px;
}
</style>
