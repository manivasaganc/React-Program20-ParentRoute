# React-Program20-ParentRoute
React-Program20-ParentRoute

import { Link, Outlet } from "react-router-dom";


function Blog(){

    return(

        <div>

            <h1>Blog Page</h1>

            <p>Select a blog post:</p>


            <nav>

                <Link to="post1">
                    React Introduction
                </Link>

                <br/>

                <Link to="post2">
                    React Router
                </Link>


            </nav>


            <hr/>


            <Outlet />


        </div>

    );

}


export default Blog;
