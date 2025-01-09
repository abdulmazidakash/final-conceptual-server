## File Structure

Install my-project with npm

```bash
└── src/
|     ├── api/
|     |		└── utils.js
|     ├── assets/
|     ├── components/
|     |	 ├── Dashboard/
|     |	 |	├── Sidebar/
|     |	 |	|	├── Menu/
|     |	 |	|	|	└── AdminMenu.jsx/
|     |	 |	|	|	└── CustomerMenu.jsx/
|     |	 |	|	|	└── MenuItem.jsx/
|     |	 |	|	|	└── SellerMenu.jsx/
|     |	 |	|	└── Sidebar.jsx/
|     |	 |	├── Statistics/
|     |	 |	|	└── AdminStatistics.jsx/
|     |	 |	├── TableRows/
|     |	 |	|	└── CustomerOrderDataRow.jsx/
|     |	 |	|	└── PlantDataRow.jsx/
|     |	 |	|	└── SellerOrderDataRow.jsx/
|     |	 |	|	└── UserDataRow.jsx/
|     |	 ├── Form/
|     |	 |	└── AddPlantForm.jsx/
|     |	 |	└── UpdatePlantForm.jsx/
|     |	 ├── Home/
|     |	 |	└── Card.jsx/
|     |	 |	└── Plants.jsx/
|     |	 ├── Modal/
|     |	 |	└── BecomeSellerModal.jsx/
|     |	 |	└── DeleteModal.jsx/
|     |	 |	└── PurchaseModal.jsx/
|     |	 |	└── UpdatePlantModal.jsx/
|     |	 |	└── UpdateUserModal.jsx/
|     |	 ├── Shared/
|     |	 |	├── Button/
|     |	 |	|	└── Button.jsx/
|     |	 |	├── Footer/
|     |	 |	|	└── Footer.jsx/
|     |	 |	├── Navbar/
|     |	 |	|	└── Navbar.jsx/
|     |	 |	└── Container.jsx/
|     |	 |	└── EmptyState.jsx/
|     |	 |	└── Heading.jsx/
|     |	 |	└── LoadingSpinner.jsx/
|     ├── firebase/
|     |	 └── firebase.config.js/
|     ├── hooks/
|     |	 └── useAuth.js/
|     |	 └── useAxiosSecure.jsx/
|     |	 └── useRole.jsx/
|     ├── layouts/
|     |	 └── DashboardLayout.jsx/
|     |	 └── MainLayout.jsx/
|     ├── pages/
|     |	 ├── Dashboard/
|     |	 |	├── Admin/
|     |	 |	|	└── ManageUsers.jsx/
|     |	 |	├── Common/
|     |	 |	|	└── Profile.jsx/
|     |	 |	|	└── Statistics.jsx/
|     |	 |	├── Customer/
|     |	 |	|	└── MyOrders.jsx/
|     |	 |	├── Seller/
|     |	 |	|	└── AddPlant.jsx/
|     |	 |	|	└── ManageOrders.jsx/
|     |	 |	|	└── MyInventory.jsx/
|     |	 ├── Home/
|     |	 |	└── Home.jsx/
|     |	 ├── Login/
|     |	 |	└── Login.jsx/
|     |	 ├── PlantDetails/
|     |	 |	└── PlantDetails.jsx/
|     |	 ├── SignUp/
|     |	 |	└── SignUp.jsx/
|     |	 └── ErrorPage.jsx/
|     ├── providers/
|     |	 └── AuthProvider.jsx/
|     ├── routes/
|     |	 └── AdminRoute.jsx/
|     |	 └── PrivateRoute.jsx/
|     |	 └── Routes.jsx/
|     |	 └── SellerRoute.jsx/
|     ├── utilities/
|     |	 ├── index.js/
└── index.css/
└── main.jsx/


```
