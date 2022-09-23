Positive Fail for INDEX:
Failures:

  1) Cats GET /index gets a list of cats
     Failure/Error: get '/cats'
     
     ActionController::MissingExactTemplate:
       CatsController#index is missing a template for request formats: text/html

Positive Fail for CREATE:
1) POST /create creates a cat
     Failure/Error: expect(response).to have_http_status(200)
       expected the response to have status code 200 but it was 204
     # ./spec/requests/cats_request_spec.rb:44:in `block (2 levels) in <top (required)>'
