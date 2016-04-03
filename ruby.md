# Ruby



# Rspec

```ruby

describe Class_name do
  it "should have a behavior" do
    expect {class.object}.to change { class.object }.by(x) 
    # OR
    expect(class.object).to eq(x)
    # OR
    object.should have(2).some_object
    # OR
    expect something.from(3).to(4)
  end
end
```
## More Matchers
```
.should respond_to
.should be_within
.should exist
.should satisfy {|x| something.x == true}
```