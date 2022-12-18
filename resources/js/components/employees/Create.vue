<template>
   <div>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-12">
                <div class="card">
                    <div class="card-header">
                        Create Employees
                        <router-link :to="{name: 'EmployeesIndex'}" class="float-right mb-2">Back</router-link>
                    </div>

                    <div class="card-body">
                        <form>

                            <div class="form-group row">
                                <label for="first_name" class="col-md-4 col-form-label text-md-right">First Name</label>

                                <div class="col-md-6">
                                    <input id="first_name" type="text" class="form-control"
                                        name="first_name" required autocomplete="first_name" autofocus>

                                   
                                </div>
                            </div>

                            <div class="form-group row">
                                <label for="middle_name" class="col-md-4 col-form-label text-md-right">Middle Name</label>

                                <div class="col-md-6">
                                    <input id="middle_name" type="text" class="form-control"
                                        name="middle_name" required autocomplete="middle_name" autofocus>

                                   
                                </div>
                            </div>

                            <div class="form-group row">
                                <label for="last_name" class="col-md-4 col-form-label text-md-right">Last Name</label>

                                <div class="col-md-6">
                                    <input id="last_name" type="text" class="form-control"
                                        name="last_name" required autocomplete="last_name" autofocus>

                                   
                                </div>
                            </div>

                            <div class="form-group row">
                                <label for="birthdate" class="col-md-4 col-form-label text-md-right">BirthDate</label>

                                <div class="col-md-6">
                                    <datepicker input-class="form-control"></datepicker>                                   
                                </div>
                            </div>

                            <div class="form-group row">
                                <label for="birthdate" class="col-md-4 col-form-label text-md-right">Date Hired</label>

                                <div class="col-md-6">
                                    <datepicker input-class="form-control"></datepicker>                                   
                                </div>
                            </div>

                            <div class="form-group row">
                                <label for="address" class="col-md-4 col-form-label text-md-right">Address</label>

                                <div class="col-md-6">
                                    <input id="address" type="text" class="form-control"
                                        name="address" required autocomplete="address" autofocus>                                   
                                </div>
                            </div>

                            <div class="form-group row">
                                <label for="zip_code" class="col-md-4 col-form-label text-md-right">Zip code</label>

                                <div class="col-md-6">
                                    <input id="zip_code" type="text" class="form-control"
                                        name="zip_code" autocomplete="zip_code" autofocus>

                                   
                                </div>
                            </div>

                            <div class="form-group row">
                                <label for="country_code"
                                    class="col-md-4 col-form-label text-md-right">Department</label>

                                <div class="col-md-6">
                                    <select name="department_id" class="form-control" aria-label="Default select example">
                                        <option selected>Select Department</option>
                                    </select>
                                </div>
                            </div>

                            <div class="form-group row">
                                <label for="country_code"
                                    class="col-md-4 col-form-label text-md-right">Country</label>

                                <div class="col-md-6">
                                    <select name="country_id" class="form-control" aria-label="Default select example">
                                        <option selected>Select Country</option>
                                    </select>
                                </div>
                            </div>

                            <div class="form-group row">
                                <label for="country_code"
                                    class="col-md-4 col-form-label text-md-right">State</label>

                                <div class="col-md-6">
                                    <select name="state_id" class="form-control" aria-label="Default select example">
                                        <option selected>Select State</option>
                                    </select>
                                </div>
                            </div>

                            <div class="form-group row">
                                <label for="country_code"
                                    class="col-md-4 col-form-label text-md-right">City</label>

                                <div class="col-md-6">
                                    <select name="city_id" class="form-control" aria-label="Default select example">
                                        <option selected>Select City</option>
                                    </select>
                                </div>
                            </div>


                            <div class="form-group row mb-0">
                                <div class="col-md-6 offset-md-4">
                                    <button type="submit" class="btn btn-primary">
                                        Store
                                    </button>
                                </div>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
   </div>
</template>

<script>
import Datepicker from 'vuejs-datepicker';
export default {
    components: {
    Datepicker
  }, data() {
    
  }

}
</script>

<style>

</style>