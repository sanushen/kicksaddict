<template>
  <q-page class="flex flex-center bg-dark row">
<!-- Left Page Section  -->
      <div class="col-12 col-md-6 left-half q-pt-md q-pb-md q-pl-md" style="height: 100vh">
      	<div class="row text-h5 q-py-md">
      		<div class="header-row">
      			<div class="header-text text-dark">KICKSADDICT</div>
      		</div>
      	</div>
        <div class="row">
	      <div class="col-5">
	        <q-img
             	src="../assets/images/img-gal-5.jpg"
				style="height: 85vh"
            />
	      </div>
	      <div class="col">
	        <div class="column" style="height: 85vh">
				<div class="col-7">
					<div class="column q-gutter-y-sm justify-evenly" style="height: 90vh">
						<div class="col-3 q-pa-sm">
							<q-img
								class=""
				             	src="../assets/images/air-force-1.png"
								style="height: 15vh"
				            />
						</div>
						<div class="col-1 q-pa-sm">
							<div class="row justify-between">
						      <div class="col-3">
						        <q-btn-dropdown
						        padding="xs"
						        dropdown-icon="fas fa-arrow-circle-down"
						        text-color="dark"
						        color="white"
						        label="UK 2.5">
							      <q-list>
							        <q-item clickable v-close-popup>
							          <q-item-section>
							            <q-item-label>UK 3.5</q-item-label>
							          </q-item-section>
							        </q-item>

							        <q-item clickable v-close-popup>
							          <q-item-section>
							            <q-item-label>UK 4.5</q-item-label>
							          </q-item-section>
							        </q-item>

							        <q-item clickable v-close-popup>
							          <q-item-section>
							            <q-item-label>UK 5.5</q-item-label>
							          </q-item-section>
							        </q-item>
							      </q-list>
							    </q-btn-dropdown>
						      </div>
						      <div class="col-8 text-h6 text-white text-uppercase text-left text-weight-bolder">
						        Nike Air Force One
						        <br/>
						        Shadow
						      </div>
						    </div>
						</div>
						<div class="col-3 q-pa-sm">
							<div class="row justify-between">
						      <div class="col-3">
						      	<q-list dense padding>
							      <q-item clickable v-ripple style="background-color: white;"/>
							      <q-item clickable v-ripple style="background-color: #57cdff;"/>
							      <q-item clickable v-ripple style="background-color: #e747b1;"/>
							      <q-item clickable v-ripple style="background-color: #b3f587;"/>
							    </q-list>

							    <div class="row q-gutter-sm">
					    		<div class="text-white">4.9</div>
								<q-rating
									v-model="ratingModel"
									size="2em"
									color="orange"
									readonly
									icon="far fa-start"
							        icon-selected="star"
							        icon-half="fas fa-star-half-alt"
									:max=1
								/>
							    </div>
						      </div>
						      <div class="col-8 text-body text-weight-light text-white text-uppercase text-left">
						        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
						      </div>
						    </div>
						</div>
						<div class="col-2 q-pa-sm">
							<div class="row">
								<div class="col">
									<q-img
						             	src="../assets/images/img-gal-3.jpg"
						            />
								</div>
								<div class="col">
									<q-img
						             	src="../assets/images/img-gal-2.jpg"
						            />
								</div>
								<div class="col">
									<q-img
						             	src="../assets/images/img-gal-1.jpg"
						            />
								</div>
								<div class="col">
									<q-img
						             	src="../assets/images/img-gal-4.jpg"
						            />
								</div>
							</div>
						</div>
					</div>
				</div>
		    </div>
	      </div>
    	</div>
    	<div class="row text-white">
    		<div class="text-h5 q-pt-lg">VIEW FULL CATALOG</div>
    		<q-separator color="white" size="px"/>
    	</div>
      </div>
<!-- Right Page Section -->
      <div class="col-12 col-md-6 right-half">
        <div class="row">
	      <div class="col-7">
	        <q-img
             	src="../assets/images/img-2.jpg"
				style="height: 100vh"
            />
	      </div>
	      <q-separator vertical size=20px style="background-image: linear-gradient(to bottom, #ce59aa, #c0e586, #26acf3, #ce59aa);"/>
	      <div class="col-4">
	        <div class="column" style="height: 90vh">
	        	<div class="col ">
			        .col
			      </div>
			      <div class="col-10 ">
			        .col-10
			      </div>
			      <div class="col ">
			        .col
			      </div>
		    </div>
	      </div>
    	</div>
      </div>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex',
  data () {
    return {
      ratingModel: 0.9
    }
  }
}
</script>

<style lang="css" scoped>
.header-row {
	right: 4%;
	background: linear-gradient(90deg, white 10%, #131313 60%);
	position: relative;
	width: 50%;
}

.header-text {
	margin-left: 8%;
}

.left-half {
}

.right-half {

}

.col-border {
	border: 2px solid white;
}
</style>
