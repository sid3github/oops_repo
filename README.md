# oops_repo

function students(firstName,lastName,age,gender){
  this.name = {
    firstName,
    lastName
  };
  this.age = age;
  this.gender = gender;
};

students.prototype.Data = function Teacher(){
  return ('hi, my name is ' + this.name.firstName);
};
