class UsersController < ApplicationController
  def new
    @user = User.new
  end

  def create
   @user = User.new params[:user]
    if @user.save(:validate=>false)
	flash[:notice] = "Thanks for Subscribe"
      redirect_to root_path
    else
  redirect_to root_path, :notice => "fdjskfhkjs"
  end
 end
end
