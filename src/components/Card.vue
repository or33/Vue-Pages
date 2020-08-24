<template>
      <div align="center" class="card" >
          <a href="#">
            <div>
            <h6>{{data.title}}</h6>
            <img :src= "data.image" class="image" v-bind:alt="data.logo" />
            <!-- <img src="../assets/apple.png" alt=""> -->
            <h3 class="time">{{data.time}}</h3>
            <p class="task">{{data.task}}</p>
            <div class="inside">
            <p class="team-no">{{data.teamNo}}</p>
            <p class="budget-no"> {{data.budgetNo}}</p>
            <p class="success-rate">{{data.successRate}}</p>
            </div>
            <div class="another-inside">
                <p class="teams">{{data.teams}}</p>
                <p class="budget">{{data.budget}}</p>
                <p class="success">{{data.success}}</p>
            </div>
            </div>
             </a>

      </div>
</template>

<script>
export default {
props: {
    data: {
        type: Object,
        requird: true
    }
}
}
</script>

<style>

* {
    margin: 0;
    padding: 0;
}
.card {
    height: 350px;
    display: inline-block;
    background: transparent;
    margin-left: 100px;
    padding: 20px 20px;
    width: 250px;
    color: black;
    font-family: 'Roboto', sans-serif;
    box-shadow: 0px 0px 0px rgb(172, 172, 172);
    -webkit-box-shadow:0px 4px 6px rgb(172, 172, 172);
    -moz-box-shadow: 0px 0px 0px rgb(172, 172, 172);

    }
a {
        text-decoration: none;
        cursor: pointer;
        color: black;
    }

.image {
        height: 90px;
        width: 100px;
        padding: 40px;
}
.time {
        font-size: 36px;
        padding-bottom: 10px;
        color: rgb(252, 227, 6);
        font-weight: lighter;
    }
.task {
    padding: 10px;
}
.inside {
    display: flex;
    padding-top: 30px;
}

.team-no {
    padding: 0 50px 0 20px;
}

.budget-no {
    padding: 0 50px 0 0;

}

.another-inside {
    display: flex;
    font-size: 12px;
    color: rgb(177, 177, 177);
}

.teams {
    padding: 0 50px 0 20px;
}

.budget {
    padding: 0 50px 0 0;
}





</style>