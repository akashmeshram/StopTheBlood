<template>
    <div>
        <h1>Train other by following</h1>
        <div>
            <br>
            <h5>Choose a Video file or Document to upload</h5>
            <div class="row">
                <form action="#" class="col s4">
                    <div class="file-field input-field">
                        <div class="btn">
                            <span>Video upload</span>
                            <input type="file">
                        </div>
                        <div class="file-path-wrapper">
                            <input class="file-path validate" type="text">
                        </div>
                    </div>
                </form>
                <form action="#" class="col s4">
                    <div class="file-field input-field">
                        <div class="btn">
                            <span>Document upload</span>
                            <input type="file">
                        </div>
                        <div class="file-path-wrapper">
                            <input class="file-path validate" type="text">
                        </div>
                    </div>
                </form>
                <form action="#" class="col s4">
                    <div class="file-field input-field">
                        <div class="btn">
                            <span>Class upload</span>
                            <input type="file">
                        </div>
                        <div class="file-path-wrapper">
                            <input class="file-path validate" type="text">
                        </div>
                    </div>
                </form>
            </div>
            <br>
            <h5>Sign up or login to submit</h5>
            <div class="row">
                <div class="col s4"><a class="btn waves-effect waves-teal red darken-1">Using google</a></div>
                <div class="col s4"><a class="btn waves-effect waves-teal indigo">Using facebook</a></div>
                <div class="col s4"><a class="btn waves-effect waves-teal black">Using E-mail</a></div>
            </div>
            <br>
            <h4><strong>OR</strong></h4>
            <h5>Sumbit as a guest</h5>
            <form action="#">
                <p>
                    <label>
                        <input class="with-gap" name="group1" type="radio" />
                        <span>Certified</span>
                    </label>
                </p>
                <p>
                    <label>
                        <input class="with-gap" name="group1" type="radio" />
                        <span>Not-Certified</span>
                    </label>
                </p>
            </form>
            <form class="col s12">
                <div class="row">
                    <div class="input-field col s6">
                        <input id="first_name" type="text" class="validate">
                        <label for="first_name">First Name</label>
                    </div>
                    <div class="input-field col s6">
                        <input id="last_name" type="text" class="validate">
                        <label for="last_name">Last Name</label>
                    </div>
                </div>
                <div class="row">
                    <div class="input-field col s12">
                        <input id="email" type="email" class="validate">
                        <label for="email">Email</label>
                    </div>
                </div>
                <button class="btn waves-effect waves-light" type="submit" name="action">Submit
                </button>
            </form>
            <br>
            <br>
        </div>
    </div>
</template>


<script>
export default {
    name: 'Register',
    props: {
        msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>