<template>
    <div class="d-flex align-items-center" style="height:100vh">
        <div class="card col-md-4 offset-md-4 shadow p-1 bg-white">
            <div class="card-header p-2">
                <h1>Authentication</h1>
                <small>Fill out the form to login </small>
            </div>
            <div class="card-body p-2">
                <form action="/action_page.php" class="needs-validation" novalidate>
                    <div class="form-group">
                        <label for="uname">Email:</label>
                        <input type="email" class="form-control form-control-sm" id="email" placeholder="" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="pwd">Password:</label>
                        <input type="password" class="form-control form-control-sm" id="password" placeholder="" name="password" required>
                    </div>
                    <div class="form-group form-check">
                        <label class="form-check-label">
                        <input class="form-check-input" type="checkbox" name="remember" required> <small>Remember me.</small>
                        <div class="valid-feedback">Valid.</div>
                        <div class="invalid-feedback">Check this checkbox to continue.</div>
                        </label>
                    </div>
                    <button type="submit" class="btn btn-primary btn-sm float-end">Submit</button>
                </form>
            </div>
        </div>
    </div>
    
    
</template>